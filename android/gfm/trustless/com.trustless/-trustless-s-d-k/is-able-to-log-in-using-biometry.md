//[trustless](../../../index.md)/[com.trustless](../index.md)/[TrustlessSDK](index.md)/[isAbleToLogInUsingBiometry](is-able-to-log-in-using-biometry.md)

# isAbleToLogInUsingBiometry

[kotlin]\
fun [isAbleToLogInUsingBiometry](is-able-to-log-in-using-biometry.md)(): Boolean

Determines whether the user has the option to authenticate using biometric credentials.

A practical application of this feature arises upon launching the app, where you may need to determine whether to prompt the user for biometric authentication.

#### Return

Boolean indicating the ability to authenticate using biometry:     - `true` if the user can authenticate with biometrics,     - `false` otherwise, indicating that biometric authentication is not available or not set up.

#### Throws

| | |
|---|---|
| [TrustlessNotInitializedSdkException](../../com.trustless.exceptions/-trustless-not-initialized-sdk-exception/index.md) | Is thrown when trying to access this method while sdk is not initialized |
