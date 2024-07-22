//[trustless](../../../index.md)/[com.trustless.requests.identity.registerUser](../index.md)/[RegisterUserRequestParams](index.md)

# RegisterUserRequestParams

class [RegisterUserRequestParams](index.md)(email: String, username: String, password: String, firstName: String? = null, lastName: String? = null, phoneNumber: String? = null) : [JSONParamsBuilder](../../com.trustless.params/-j-s-o-n-params-builder/index.md)

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

## Constructors

| | |
|---|---|
| [RegisterUserRequestParams](-register-user-request-params.md) | [kotlin]<br>constructor(email: String, username: String, password: String, firstName: String? = null, lastName: String? = null, phoneNumber: String? = null) |
