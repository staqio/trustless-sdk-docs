//[trustless](../../../index.md)/[com.trustless.providers](../index.md)/[IdentityProvider](index.md)/[passwordResetConfirm](password-reset-confirm.md)

# passwordResetConfirm

[kotlin]\
abstract suspend fun [passwordResetConfirm](password-reset-confirm.md)(params: [PasswordRecoveryConfirmRequestParams](../../com.trustless.requests.identity.passwordRecoveryConfirm/-password-recovery-confirm-request-params/index.md))

Confirm password reset

#### Parameters

kotlin

| | |
|---|---|
| params | params to confirm of reset of a password |

#### Throws

| | |
|---|---|
| [TrustlessException](../../com.trustless.exceptions/-trustless-exception/index.md) | Is thrown when the server returns custom error, or when error was not expected by the SDK |
| [TrustlessAppTokenException](../../com.trustless.exceptions/-trustless-app-token-exception/index.md) | Is thrown when the token expires, either due to time period or server forced expiration |
| [TrustlessMalformedResponse](../../com.trustless.exceptions/-trustless-malformed-response/index.md) | Is thrown when server returned unexpected format of the data |
| [TrustlessExceptionListener](../../com.trustless.exceptions/-trustless-exception-listener/index.md) | Is thrown when developer has not set security listener |
| [TrustlessExceptionSecurityProviderIsNotInstalled](../../com.trustless.exceptions/-trustless-exception-security-provider-is-not-installed/index.md) | Is thrown when user's device doesn't have a security provider |
| CancellationException | Is thrown usually when the developer cancels the coroutine |
| [TrustlessNotInitializedSdkException](../../com.trustless.exceptions/-trustless-not-initialized-sdk-exception/index.md) | Is thrown when trying to access this method while sdk is not initialized |
