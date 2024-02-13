//[trustless](../../../index.md)/[com.trustless](../index.md)/[TrustlessSDK](index.md)/[passwordResetConfirm](password-reset-confirm.md)

# passwordResetConfirm

[kotlin]\
suspend fun [passwordResetConfirm](password-reset-confirm.md)(params: [PasswordRecoveryConfirmRequestParams](../../com.trustless.requests.identity.passwordRecoveryConfirm/-password-recovery-confirm-request-params/index.md))

Confirm password reset

[Server Api Reference](https://developer.staq.io/docs/apis/identity#/User%20management/Confirm%20password%20reset)

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
| CancellationException | Is thrown usually when the developer cancels the coroutine |
