//[trustless](../../../index.md)/[com.trustless.requests.identity.updateUser](../index.md)/[UpdateUserRequestParams](index.md)

# UpdateUserRequestParams

class [UpdateUserRequestParams](index.md)(firstName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, lastName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, phoneNumber: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?) : [JSONParamsBuilder](../../com.trustless.params/-j-s-o-n-params-builder/index.md)

[Server Api Reference](https://developer.staq.io/docs/apis/identity#/User%20management/Update%20a%20user)

#### Parameters

kotlin

| | |
|---|---|
| firstName | First name of the application user |
| lastName | Last name of the application user |
| phoneNumber | Phone number of the application user. Should start from a + (plus), no zero as a first digit is allowed. |

#### Throws

| |
|---|
| [TrustlessInvalidNameException](../../com.trustless.exceptions/-trustless-invalid-name-exception/index.md) |
| [TrustlessPhoneNumberException](../../com.trustless.exceptions/-trustless-phone-number-exception/index.md) |

## Constructors

| | |
|---|---|
| [UpdateUserRequestParams](-update-user-request-params.md) | [kotlin]<br>constructor(firstName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, lastName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, phoneNumber: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?) |
