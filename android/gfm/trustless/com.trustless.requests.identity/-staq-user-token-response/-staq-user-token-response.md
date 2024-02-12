//[trustless](../../../index.md)/[com.trustless.requests.identity](../index.md)/[StaqUserTokenResponse](index.md)/[StaqUserTokenResponse](-staq-user-token-response.md)

# StaqUserTokenResponse

[kotlin]\
constructor(accessToken: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), tokenType: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), expiresIn: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), scope: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), refreshToken: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), refreshExpiresIn: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))

#### Parameters

kotlin

| | |
|---|---|
| accessToken | Access token to invoke Finto API methods MINLENGTH: 1 |
| tokenType | Type of token MINLENGTH: 1 |
| expiresIn | Token lifetime in seconds MAXIMUM: 2147483647 MINIMUM: 0 |
| scope | Scope name. Indicates the API that application is going to access with the token. MINLENGTH: 1 |
| refreshToken | Refresh token for the access token MINLENGTH: 1 |
| refreshExpiresIn | Token lifetime in seconds |
