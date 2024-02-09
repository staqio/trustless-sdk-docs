
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
        implementation("com.staq:trustless:1.0.0")
    }
```

# Initialization
To use TrustlessSdk, you must first obtain a client certificate and credentials (`clientId` and `clientSecret`). Follow these steps:

1. Obtain a Client Certificate:
    - Visit Staq Certificate Management and follow the instructions to acquire a certificate in PFX format.
2. Obtain Client ID and Client Secret:
    - Go to Staq Applications Management for details on obtaining your clientId and clientSecret.
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
override fun onDestroyView() {
    super.onDestroyView()
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