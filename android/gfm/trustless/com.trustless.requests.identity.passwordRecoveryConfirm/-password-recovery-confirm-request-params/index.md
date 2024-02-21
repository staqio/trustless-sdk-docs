//[trustless](../../../index.md)/[com.trustless.requests.identity.passwordRecoveryConfirm](../index.md)/[PasswordRecoveryConfirmRequestParams](index.md)

# PasswordRecoveryConfirmRequestParams

class [PasswordRecoveryConfirmRequestParams](index.md)constructor(email: String, code: String, password: String) : [JSONParamsBuilder](../../com.trustless.params/-j-s-o-n-params-builder/index.md)

[Server Api Reference](https://developer.staq.io/docs/apis/identity#/User%20management/Confirm%20password%20reset)

#### Parameters

kotlin

| | |
|---|---|
| email | Email of the application user |
| code | OTP code |
| password | New password of the application user |

#### Throws

| |
|---|
| [TrustlessEmailException](../../com.trustless.exceptions/-trustless-email-exception/index.md) |
| [TrustlessCodeException](../../com.trustless.exceptions/-trustless-code-exception/index.md) |
| [TrustlessPasswordException](../../com.trustless.exceptions/-trustless-password-exception/index.md) |

## Constructors

| | |
|---|---|
| [PasswordRecoveryConfirmRequestParams](-password-recovery-confirm-request-params.md) | [kotlin]<br>constructor(email: String, code: String, password: String) |
