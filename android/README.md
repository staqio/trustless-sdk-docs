
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
            url = uri("...")
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

# API Reference
[API](gfm/index.md)
# Support
Contact support@staq.io for support.