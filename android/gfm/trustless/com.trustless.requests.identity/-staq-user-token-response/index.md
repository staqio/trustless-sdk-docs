//[trustless](../../../index.md)/[com.trustless.requests.identity](../index.md)/[StaqUserTokenResponse](index.md)

# StaqUserTokenResponse

[kotlin]\
@Serializable

data class [StaqUserTokenResponse](index.md)(val accessToken: String, val tokenType: String, val expiresIn: Int, val scope: String, val refreshToken: String, val refreshExpiresIn: Int)

## Constructors

| | |
|---|---|
| [StaqUserTokenResponse](-staq-user-token-response.md) | [kotlin]<br>constructor(accessToken: String, tokenType: String, expiresIn: Int, scope: String, refreshToken: String, refreshExpiresIn: Int) |

## Properties

| Name | Summary |
|---|---|
| [accessToken](access-token.md) | [kotlin]<br>@SerialName(value = &quot;access_token&quot;)<br>val [accessToken](access-token.md): String<br>Access token to invoke Finto API methods MINLENGTH: 1 |
| [expiresIn](expires-in.md) | [kotlin]<br>@SerialName(value = &quot;expires_in&quot;)<br>val [expiresIn](expires-in.md): Int<br>Token lifetime in seconds MAXIMUM: 2147483647 MINIMUM: 0 |
| [refreshExpiresIn](refresh-expires-in.md) | [kotlin]<br>@SerialName(value = &quot;refresh_expires_in&quot;)<br>val [refreshExpiresIn](refresh-expires-in.md): Int<br>Token lifetime in seconds |
| [refreshToken](refresh-token.md) | [kotlin]<br>@SerialName(value = &quot;refresh_token&quot;)<br>val [refreshToken](refresh-token.md): String<br>Refresh token for the access token MINLENGTH: 1 |
| [scope](scope.md) | [kotlin]<br>val [scope](scope.md): String<br>Scope name. Indicates the API that application is going to access with the token. MINLENGTH: 1 |
| [tokenType](token-type.md) | [kotlin]<br>@SerialName(value = &quot;token_type&quot;)<br>val [tokenType](token-type.md): String<br>Type of token MINLENGTH: 1 |
