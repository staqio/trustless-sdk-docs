//[trustless](../../../index.md)/[com.trustless.requests.identity.registerUser](../index.md)/[RegisterUserRequestParams](index.md)

# RegisterUserRequestParams

class [RegisterUserRequestParams](index.md)(email: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), username: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), password: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), firstName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, lastName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, phoneNumber: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?) : [JSONParamsBuilder](../../com.trustless.params/-j-s-o-n-params-builder/index.md)

[Server Api Reference](https://developer.staq.io/docs/apis/identity#/User%20management/Create%20a%20user)

#### Parameters

kotlin

| | |
|---|---|
| email | Email of the application user |
| username | Username of the application user |
| password | Password of the application user |
| firstName | First name of the application user |
| lastName | Last name of the application user |
| phoneNumber | Phone number of the application user. Should start from a + (plus), no zero as a first digit is allowed. |

#### Throws

| |
|---|
| [TrustlessEmailException](../../com.trustless.exceptions/-trustless-email-exception/index.md) |
| [TrustlessPasswordException](../../com.trustless.exceptions/-trustless-password-exception/index.md) |
| [TrustlessInvalidNameException](../../com.trustless.exceptions/-trustless-invalid-name-exception/index.md) |
| [TrustlessPhoneNumberException](../../com.trustless.exceptions/-trustless-phone-number-exception/index.md) |

## Constructors

| | |
|---|---|
| [RegisterUserRequestParams](-register-user-request-params.md) | [kotlin]<br>constructor(email: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), username: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), password: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), firstName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, lastName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, phoneNumber: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?) |