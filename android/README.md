
# Introduction
TrustlessSdk simplifies developers' interactions with the Staq APIs, into your Android applications. It provides a comprehensive set of tools designed to facilitate secure and efficient communication with Staq's infrastructure.


# Prerequisites
- Minimum SDK version (`minSdk`) of 30.
- Compilation against SDK version (`compileSdk`) of 34.

# Installation
To add TrustlessSdk to your project, update your build configuration as follows:

1. Add the Maven repository to your project-level `build.gradle` file:
```kotlin
    repositories {
        maven {
            url = uri("https://repo.staq.io/repository/trustless-sdk/")
        }
    }
```
2. Include TrustlessSdk as a dependency in your app-level `build.gradle` file:


```kotlin
    dependencies {
        implementation("com.staq:trustless:2.0.0")
    }
```

# Initialization
To use TrustlessSdk, you must first obtain a client certificate and credentials (`clientId` and `clientSecret`). Follow these steps:

1. Obtain a Client Certificate:
    - Visit [Staq Certificate Management](https://developer.staq.io/docs/guides/sandbox/certificates-management) and follow the instructions to acquire a certificate in PFX format.
2. Obtain Client ID and Client Secret:
    - Go to [Staq Applications Management](https://developer.staq.io/docs/guides/sandbox/applications-management) for details on obtaining your clientId and clientSecret.
3. Initialize TrustlessSdk in your application:

```kotlin


    override fun onCreate(savedInstanceState: Bundle?) {

        val inputStream = resources.openRawResource(R.raw.staq)
        val clientCertificate = ClientCertificate(inputStream.toByteArray(), "your password")

        val configuration = TrustlessConfiguration(
            "clientId",
            "clientSecret",
            clientCertificate,
        )

        try {
            TrustlessSDK.initialize(configuration, applicationContext)
        } catch (e: TrustlessException) {
            // Handle initialization errors here.
        }
    }
```
Optionally, customize the SDK initialization by adding your own `OkHttp` client to the `TrustlessConfiguration` as the last parameter for advanced networking configurations.

## Security Provider
The Security Provider feature in Android enables applications to address SSL vulnerabilities dynamically, without the need to modify the app's source code directly. This capability is crucial for maintaining the security integrity of your application by ensuring it uses the most up-to-date encryption protocols and standards.
### Subscribing to Security Provider Updates
To leverage this feature, `TrustlessSDK` offers a subscription mechanism that triggers a callback when an update to the Security Provider is necessary. Implement the subscription as follows:

```kotlin
TrustlessSDK.instance.subscribeToSecurityProviderUpdate { errorCode, _ ->
        GoogleApiAvailability.getInstance().apply {
            if (isUserResolvableError(errorCode)) {
                 // If the error is resolvable by the user, show an error dialog prompting them to update the Security Provider.
                showErrorDialogFragment(this@MainActivity, errorCode, SECURITY_PROVIDER_CODE) {
                     // Callback for when the user's intervention fails or is not feasible.

                    TrustlessSDK.instance.securityProviderFailedAsync()
                }
            } else {
                // If the error cannot be resolved by the user, directly notify the failure to handle internally.
                TrustlessSDK.instance.securityProviderFailedAsync()
            }
        }
    }
```
This setup ensures your application attempts to update the Security Provider automatically and handles scenarios where the update cannot be completed, notifying TrustlessSDK to take appropriate action. Keep in mind that if it fails the user won't be able to use the app.

### Handling Update Success

To inform the SDK about the successful update of the Security Provider, especially after user intervention, override `onActivityResult`:

```kotlin
override fun onActivityResult(requestCode: Int, resultCode: Int, data: Intent?) {
        super.onActivityResult(requestCode, resultCode, data)
        if (requestCode == SECURITY_PROVIDER_CODE) {
              // Notifies the SDK that the Security Provider update was successful.
            TrustlessSDK.instance.securityProviderSuccessAsync()
        }
    }
```
This method is crucial for the SDK to recognize the update's success, ensuring your application continues to operate with the latest security standards.

# Basic Usage
Interact with Staq APIs using the `TrustlessSDK` class. Here’s how to register a new user:

1. Import necessary classes:
```kotlin
import com.trustless.TrustlessSDK
import com.trustless.requests.identity.registerUser.RegisterUserRequestParams
```
2. Execute the API call within a coroutine scope, handle the parameters and errors:

```kotlin
lifecycleScope.launch {
    try {
            val params = RegisterUserRequestParams(
                email.getTextString(),
                username.getTextString(),
                password.getTextString(),
                firstName.getTextString(),
                lastName.getTextString(),
                phoneNumber.getTextString()
            )
            val result = TrustlessSDK.registerUser(params)
            // Use the result of the registration process here.
        } catch (e: TrustlessException) {
            // handle error
        }
}
```
3. Handle `exceptions`, every exception is inherited from `TrustlessException`
## Usage Of Paginator
Facilitates pagination by encapsulating the logic required to manage paginated requests.

1. Initializing the Paginator
```kotlin
val paginator = TrustlessSDK.instance.getAccounts(
        13,
        1
    )
```
2. Fetching the First Page
```kotlin
try {
    val res = repository.fetchFirst().data
} catch (e: TrustlessException) {
    // Handle error
}
```
3. Fetching Subsequent Pages, you can then append this new data to your existing dataset
```kotlin
val res = paginator.fetchNext().data
val newData = _state.value.data + res
```

## Usage Of `StaqRequest` class
The `StaqRequest` class in the TrustlessSDK is designed to facilitate safe, repeatable operations—particularly useful for financial transactions where the integrity and non-duplication of requests are crucial. If a request encounters a failure, you can safely retry the same request without worrying about unintended duplications of the operation on the server side. However, to leverage this feature, it's essential to persist the request object between attempts, and having the same arguments


1. Creating a Request Object, it usually accepts a non changing parameter like account number

```kotlin
val request = TrustlessSDK.instance.getTopUpCardRequest(value)
```
2. Executing the Request
```kotlin
val params = ChangeCardBalanceParams(
            account.number,
            amount,
            account.currencyCode
        )
request.call(params)
```




# Advanced Usage
## KYC Module
1. You need to obtain the steps for the onboarding process by calling with the source map
```kotlin
TrustlessSDK.instance.getSteps(sourceMap)
```
SourceFieldsMap object is not copied, the reference to your instance is saved. This object is used to save data from the KYCSDK step, you should save this object persist it throughout onboarding process.

The value you get is instance of `AllKYCSteps` class
you can use to retrieve steps, each step represents one screen.
`steps.getSteps()`

if `step.isKyc()` returns `true`, this means that on this step you need to perform actions to obtain these parameters, and put them inside `sourceMap` object which you created in the previous step:

next fields are part of a mrz, and can be obtained by reading document mrz
- `optionalDataFirstLine`
- `nationality`
- `fullName`
- `documentNumber`
- `dateOfExpiry`
- `dateOfBirth`
- `gender`

next fields are files.
- `frontCard`: front document scan
- `backCard`: back document scan
- `selfieImage`: selfie capture
- `selfieVideo`: recorded video of a person

## Page Display and Validation
To interact with and validate page fields, follow these guidelines:
### Field Types
Each field on a page comes with a specific type that dictates its content and interaction requirements:
- `BooleanField`: Accepts a `true` or `false` value. If `webViewUrl` is provided, display terms or conditions via a `WebView`.
- `DateField`: Requires a date in `dd-mm-yyyy` format.
- `DocumentField`: A file upload is required.
- `IntegerField`: Accepts integer values only.
- `ListOfValuesField`: A selection from provided options is required. Use `fieldManager.getChoicesEn()` or `fieldManager.getChoicesAr()` to obtain the choices.
- `ProofDocumentField`: Requires multiple documents to be uploaded.
- `TextField`: Accepts a string.
- `UrlField`: Similar to `ListOfValuesField`, but the data is fetched from the server.
```kotlin
val dependentValue = fieldManager.getValueFromDependentField() ?: return
if (!fieldManager.hasDependentFieldChanged()) {
    return
}
val res = TrustlessSDK.instance.getCityList(dependentValue)
val choices = HashMap<String, String>()
for (el in res) {
    choices[el.code] = el.city
}
// same for choicesAr
fieldManager.setChoices(choices, choicesAr)
```
### Displaying a WebView
For fields where `webViewUrl` is not an empty string, display a WebView to show the linked content. This is commonly used for presenting terms and conditions associated with a `BooleanField`.

### Validation Process
To validate the current page:
1. Call `Page.fields` to retrieve an array of errors.
2. If the array is not empty, the page is considered invalid. Display the first error message using:
```kotlin
errorTextView.setText(fieldManager.validate()[0].messageEn)
```
### Submission Process
Upon reaching the last question and confirming the page is valid:
1. Construct the JSON payload with `allSteps.getJSON()`.
2. Gather documents using `allSteps.getDocumentsMap()`.
3. Submit the KYC data with:

```kotlin
val json = allSteps.getJSON()
val documents = allSteps.getDocumentsMap()
val res = TrustlessSDK.instance.uploadKyc(
            json.toString(),
            documents
        )
```

## Deinitialization
To ensure efficient memory management and clean up resources utilized by the Trustless SDK, incorporate the following code snippet when the SDK is no longer needed, typically during the shutdown or cleanup phase of your application:
```kotlin
TrustlessSDK.deinitialize()
```
### Managing User Logout
#### Clearing User Data
To securely remove user-specific data from memory, utilize the `logout` method provided by the Trustless SDK. This method is essential for maintaining user privacy and security by ensuring that sensitive information is not retained in memory longer than necessary.

#### Handling Token Expiration

The Trustless SDK provides a mechanism to detect and respond to the expiration of a user's authentication token. When the token expires, subsequent API requests will fail. To handle this scenario gracefully, register a logout listener as follows:

```kotlin
TrustlessSDK.instance.setLogoutListener {
    lifecycleScope.launch {
        try {
            showLoader()
            TrustlessSDK.instance.logout()
            requireActivity().viewModelStore.clear()
        } catch (e: TrustlessException) {
            showToast(e.message)
        } finally {
            hideLoader()
            findNavController().popBackStack(R.id.navigation_start, false)
        }
    }
}
```
This listener ensures that you can perform necessary cleanup and UI updates when a logout is initiated, either manually or due to token expiration.

#### Unregistering the Logout Listener
To prevent potential memory leaks and ensure that callbacks do not occur after a user has logged out or when your UI component (such as a Fragment or Activity) is destroyed, unregister the logout listener. This is particularly important in Android applications to manage lifecycle events effectively:
```kotlin
override fun onDestroy() {
    super.onDestroy()
    TrustlessSDK.instance.clearLogoutListener()
}
```
Place this code in the `onDestroyView` method of your Fragment or the `onDestroy` method of your Activity to ensure the listener is removed at the appropriate time in the lifecycle.
## Biometry
To enable biometric authentication within your application, follow the steps outlined below. This process ensures a secure and user-friendly authentication experience:

Initiate the login process by calling `login` on the `TrustlessSDK` instance, setting the `useBiometry` option to `true`:
```kotlin
val params = UserTokenRequestParams(
                    usernameEditText.getTextString(),
                    passwordEditText.getTextString()
                )
TrustlessSDK.instance.login(params, true)
```
To handle biometry requests from the SDK, subscribe to biometry requests using `subscribeToBiometryRequest`. Inside this subscription, implement the logic to prompt the user for biometric authentication:
```kotlin
TrustlessSDK.instance.subscribeToBiometryRequest {
    // Implement the prompt for biometric authentication here.
}
```
After the user successfully completes the biometric authentication, notify the SDK by calling `userWasAuthenticated`. This step is crucial for resuming any pending requests that require authentication confirmation:
```kotlin
TrustlessSDK.instance.userWasAuthenticated()
```
**`Note`**: The SDK automatically checks the biometry status during requests. If biometric authentication is necessary, it will pause the current request. To continue, you must invoke `TrustlessSDK.instance.userWasAuthenticated()` after the user passes the biometric check.

# Miscellaneous
## KYC ID and Customer ID
To obtain the KYC ID use:
```kotlin
TrustlessSDK.instance.retrieveCustomerId()
```

For acquiring the unique identifier associated with a customer, execute:
```kotlin
TrustlessSDK.instance.retrieveKycId()
```
Both identifiers are fetched as needed and stored in the cache to minimize redundant network requests and optimize performance.

To clear the cache, including stored KYC and customer IDs, use the following method:
```kotlin
TrustlessSDK.instance.logout()
```



# API Reference
[API](gfm/index.md)
# Support
Contact support@staq.io for support.

# Changelog
## v2.0.0
Split methods in different providers.
# Migration Guides
## From v1.x.x to v2.x.x
In the transition from version 1.x.x to version 2.x.x of the TrustlessSDK, several methods have been relocated within the SDK's structure
### Accounts
- Before `TrustlessSDK.instance.getAccounts()`
- After  `TrustlessSDK.accountsProvider.getAccounts()`

Do the same for the following methods: `getAccountByNumber`,`createAnAccount`,`getAccounts`,`getAccountTransactions`,`deleteAccountByNumber`
### Cards
- Before `TrustlessSDK.instance.getCards()`
- After  `TrustlessSDK.cardsProvider.getCards()`

Do the same for the following methods: `createCard`,`getCards`,`getActiveCards`,`changeCardStatus`,`getCardByToken`,`getCardTransactions`,`changeCardMobileNumber`,`getPanByToken`,`getBalances`,`getLimits`,`setLimits`,`getCVVByToken`,`getTopUpCardRequest`,`getWithdrawFromCardRequest`

### CliQ
- Before `TrustlessSDK.instance.getAliases()`
- After  `TrustlessSDK.cliqProvider.getAliases()`

Do the same for the following methods: `getPurposes`,`createAlias`,`getAliases`

### Identity
- Before `TrustlessSDK.instance.logout()`
- After  `TrustlessSDK.identityProvider.logout()`

Do the same for the following methods: `login`,`registerUser`,`updatePassword`,`resetPassword`,`passwordResetConfirm`,`updateUser`,`retrieveUser`,`logout`

### KYC
- Before `TrustlessSDK.instance.getSteps()`
- After  `TrustlessSDK.kycProvider.getSteps()`

Do the same for the following methods: `getCityList`,`retrieveCustomerId`,`retrieveKycId`,`getSteps`,`uploadKyc`

### Simulation
- Before `TrustlessSDK.instance.approveKyc()`
- After  `TrustlessSDK.simulationProvider.approveKyc()`

Do the same for the following methods: `approveKyc`, `setAccountBalance`

### Transfers
- Before `TrustlessSDK.instance.getTransfers()`
- After  `TrustlessSDK.simulationProvider.getTransfers()`

Do the same for the following methods: `getTransfers`,`createInternalTransfer`,`createCliqTransfer`,`confirmTransfer`,`getTransferById`