//[trustless](../../../index.md)/[com.trustless.requests.identity](../index.md)/[StaqTokenResponse](index.md)

# StaqTokenResponse

[kotlin]\
@Serializable

data class [StaqTokenResponse](index.md)(val accessToken: String, val tokenType: String, val expiresIn: Int, val scope: String)

## Constructors

| | |
|---|---|
| [StaqTokenResponse](-staq-token-response.md) | [kotlin]<br>constructor(accessToken: String, tokenType: String, expiresIn: Int, scope: String) |

## Properties

| Name | Summary |
|---|---|
| [accessToken](access-token.md) | [kotlin]<br>@SerialName(value = &quot;access_token&quot;)<br>val [accessToken](access-token.md): String |
| [expiresIn](expires-in.md) | [kotlin]<br>@SerialName(value = &quot;expires_in&quot;)<br>val [expiresIn](expires-in.md): Int |
| [scope](scope.md) | [kotlin]<br>val [scope](scope.md): String |
| [tokenType](token-type.md) | [kotlin]<br>@SerialName(value = &quot;token_type&quot;)<br>val [tokenType](token-type.md): String |
