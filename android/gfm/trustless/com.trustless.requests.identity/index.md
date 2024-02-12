//[trustless](../../index.md)/[com.trustless.requests.identity](index.md)

# Package-level declarations

## Types

| Name | Summary |
|---|---|
| [StaqRegisterUserResponse](-staq-register-user-response/index.md) | [kotlin]<br>@Serializable<br>data class [StaqRegisterUserResponse](-staq-register-user-response/index.md)(val username: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val phoneNumber: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val email: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val lastName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val firstName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |
| [StaqRetrieveUserResponse](-staq-retrieve-user-response/index.md) | [kotlin]<br>@Serializable<br>data class [StaqRetrieveUserResponse](-staq-retrieve-user-response/index.md)(val username: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val email: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val firstName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val lastName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val phoneNumber: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |
| [StaqTokenResponse](-staq-token-response/index.md) | [kotlin]<br>@Serializable<br>data class [StaqTokenResponse](-staq-token-response/index.md)(val accessToken: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val tokenType: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val expiresIn: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), val scope: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |
| [StaqUserTokenResponse](-staq-user-token-response/index.md) | [kotlin]<br>@Serializable<br>data class [StaqUserTokenResponse](-staq-user-token-response/index.md)(val accessToken: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val tokenType: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val expiresIn: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), val scope: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val refreshToken: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val refreshExpiresIn: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |