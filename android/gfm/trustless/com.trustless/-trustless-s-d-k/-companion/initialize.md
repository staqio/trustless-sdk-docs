//[trustless](../../../../index.md)/[com.trustless](../../index.md)/[TrustlessSDK](../index.md)/[Companion](index.md)/[initialize](initialize.md)

# initialize

[kotlin]\
fun [initialize](initialize.md)(configuration: [TrustlessConfiguration](../../../com.trustless.requests.utils/-trustless-configuration/index.md), context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html))

Initializes the TrustlessSDK with the provided configuration and application context. This step is essential for the SDK to function correctly. Without initialization, the SDK operations will not be executed as expected. Ensure this method is called once during your application's startup, typically in your Application class or main activity's onCreate method.

#### Parameters

kotlin

| | |
|---|---|
| configuration | The configuration settings for the TrustlessSDK |
| context | The application context used by the SDK for accessing resources and performing operations     that require a context. |

#### Throws

| | |
|---|---|
| [TrustlessCertificateException](../../../com.trustless.exceptions/-trustless-certificate-exception/index.md) | Is thrown when the certificate are not able to load |
