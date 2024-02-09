//[trustless](../../../index.md)/[com.trustless](../index.md)/[TrustlessSDK](index.md)/[subscribeToBiometryRequest](subscribe-to-biometry-request.md)

# subscribeToBiometryRequest

[kotlin]\
fun [subscribeToBiometryRequest](subscribe-to-biometry-request.md)(listener: () -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html))

Registers a callback to be invoked when biometric authentication is required. This function allows the application to respond to SDK requests for biometric authentication, typically by prompting the user to authenticate using their biometric credentials (e.g., fingerprint, facial recognition).

#### Parameters

kotlin

| | |
|---|---|
| listener | A callback that will be executed when the SDK requires biometric authentication.     The application should implement this callback to trigger the biometric authentication process. |
