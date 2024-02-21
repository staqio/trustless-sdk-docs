//[trustless](../../../index.md)/[com.trustless.requests.cliq](../index.md)/[StaqAliasDetails](index.md)

# StaqAliasDetails

[kotlin]\
@Serializable

data class [StaqAliasDetails](index.md)(val type: String, val value: String, val startDate: String, val expirationDate: String, val status: String, val accounts: List&lt;[StaqAccount](../-staq-account/index.md)&gt;)

Alias Details Object

## Constructors

| | |
|---|---|
| [StaqAliasDetails](-staq-alias-details.md) | [kotlin]<br>constructor(type: String, value: String, startDate: String, expirationDate: String, status: String, accounts: List&lt;[StaqAccount](../-staq-account/index.md)&gt;) |

## Properties

| Name | Summary |
|---|---|
| [accounts](accounts.md) | [kotlin]<br>@SerialName(value = &quot;Accounts&quot;)<br>val [accounts](accounts.md): List&lt;[StaqAccount](../-staq-account/index.md)&gt;<br>accounts list |
| [expirationDate](expiration-date.md) | [kotlin]<br>@SerialName(value = &quot;ExpirationDate&quot;)<br>val [expirationDate](expiration-date.md): String<br>Cliq Alias expiration date |
| [startDate](start-date.md) | [kotlin]<br>@SerialName(value = &quot;StartDate&quot;)<br>val [startDate](start-date.md): String<br>Cliq Alias start date |
| [status](status.md) | [kotlin]<br>@SerialName(value = &quot;Status&quot;)<br>val [status](status.md): String<br>Cliq Alias status |
| [type](type.md) | [kotlin]<br>@SerialName(value = &quot;Type&quot;)<br>val [type](type.md): String<br>Cliq Alias type ENUM:  ALIAS, MOBL |
| [value](value.md) | [kotlin]<br>@SerialName(value = &quot;Value&quot;)<br>val [value](value.md): String<br>Cliq Alias value |
