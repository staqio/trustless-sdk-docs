//[trustless](../../../index.md)/[com.trustless.requests.identity](../index.md)/[StaqRegisterUserResponse](index.md)

# StaqRegisterUserResponse

[kotlin]\
@Serializable

data class [StaqRegisterUserResponse](index.md)(val username: String, val id: String, val phoneNumber: String, val email: String, val lastName: String, val firstName: String)

## Constructors

| | |
|---|---|
| [StaqRegisterUserResponse](-staq-register-user-response.md) | [kotlin]<br>constructor(username: String, id: String, phoneNumber: String, email: String, lastName: String, firstName: String) |

## Properties

| Name | Summary |
|---|---|
| [email](email.md) | [kotlin]<br>@SerialName(value = &quot;Email&quot;)<br>val [email](email.md): String<br>Email of the application user |
| [firstName](first-name.md) | [kotlin]<br>@SerialName(value = &quot;FirstName&quot;)<br>val [firstName](first-name.md): String<br>First name of the application user |
| [id](id.md) | [kotlin]<br>@SerialName(value = &quot;Id&quot;)<br>val [id](id.md): String<br>Id of the application user |
| [lastName](last-name.md) | [kotlin]<br>@SerialName(value = &quot;LastName&quot;)<br>val [lastName](last-name.md): String<br>Last name of the application user |
| [phoneNumber](phone-number.md) | [kotlin]<br>@SerialName(value = &quot;PhoneNumber&quot;)<br>val [phoneNumber](phone-number.md): String<br>Phone number of the application user |
| [username](username.md) | [kotlin]<br>@SerialName(value = &quot;Username&quot;)<br>val [username](username.md): String<br>Username of the application user |
