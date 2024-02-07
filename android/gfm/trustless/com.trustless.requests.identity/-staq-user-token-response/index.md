//[trustless](../../../index.md)/[com.trustless.requests.identity](../index.md)/[StaqUserTokenResponse](index.md)

# StaqUserTokenResponse

[kotlin]\
@Serializable

data class [StaqUserTokenResponse](index.md)(val accessToken: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val tokenType: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val expiresIn: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), val scope: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val refreshToken: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val refreshExpiresIn: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))

## Constructors

| | |
|---|---|
| [StaqUserTokenResponse](-staq-user-token-response.md) | [kotlin]<br>constructor(accessToken: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), tokenType: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), expiresIn: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), scope: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), refreshToken: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), refreshExpiresIn: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |

## Properties

| Name | Summary |
|---|---|
| [accessToken](access-token.md) | [kotlin]<br>@SerialName(value = &quot;access_token&quot;)<br>val [accessToken](access-token.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [expiresIn](expires-in.md) | [kotlin]<br>@SerialName(value = &quot;expires_in&quot;)<br>val [expiresIn](expires-in.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [refreshExpiresIn](refresh-expires-in.md) | [kotlin]<br>@SerialName(value = &quot;refresh_expires_in&quot;)<br>val [refreshExpiresIn](refresh-expires-in.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [refreshToken](refresh-token.md) | [kotlin]<br>@SerialName(value = &quot;refresh_token&quot;)<br>val [refreshToken](refresh-token.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [scope](scope.md) | [kotlin]<br>val [scope](scope.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [tokenType](token-type.md) | [kotlin]<br>@SerialName(value = &quot;token_type&quot;)<br>val [tokenType](token-type.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
