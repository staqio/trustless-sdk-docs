//[trustless](../../../../index.md)/[com.trustless](../../index.md)/[TrustlessSDK](../index.md)/[Companion](index.md)

# Companion

[kotlin]\
object [Companion](index.md)

## Properties

| Name | Summary |
|---|---|
| [instance](instance.md) | [kotlin]<br>val [instance](instance.md): [TrustlessSDK](../index.md)<br>Provides access to the current instance of the TrustlessSDK. This instance is lazily initialized, ensuring that it is created only when needed. |

## Functions

| Name | Summary |
|---|---|
| [deinitialize](deinitialize.md) | [kotlin]<br>fun [deinitialize](deinitialize.md)()<br>Cleans up the SDK's allocated resources and resets its state. This function should be called when the SDK is no longer needed, typically at the application's shutdown. |
| [initialize](initialize.md) | [kotlin]<br>fun [initialize](initialize.md)(configuration: [TrustlessConfiguration](../../../com.trustless.requests.utils/-trustless-configuration/index.md), context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html))<br>Initializes the TrustlessSDK with the provided configuration and application context. This step is essential for the SDK to function correctly. Without initialization, the SDK operations will not be executed as expected. Ensure this method is called once during your application's startup, typically in your Application class or main activity's onCreate method. |
