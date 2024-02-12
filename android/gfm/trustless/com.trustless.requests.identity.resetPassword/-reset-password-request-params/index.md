//[trustless](../../../index.md)/[com.trustless.requests.identity.resetPassword](../index.md)/[ResetPasswordRequestParams](index.md)

# ResetPasswordRequestParams

class [ResetPasswordRequestParams](index.md)(oldPassword: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), newPassword: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) : [JSONParamsBuilder](../../com.trustless.params/-j-s-o-n-params-builder/index.md)

[Server Api Reference](https://developer.staq.io/docs/apis/identity#/User%20management/Set%20password)

#### Parameters

kotlin

| | |
|---|---|
| oldPassword | Current password of the application user |
| newPassword | New password of the application user |

#### Throws

| |
|---|
| [TrustlessPasswordException](../../com.trustless.exceptions/-trustless-password-exception/index.md) |

## Constructors

| | |
|---|---|
| [ResetPasswordRequestParams](-reset-password-request-params.md) | [kotlin]<br>constructor(oldPassword: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), newPassword: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |
