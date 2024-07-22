//[trustless](../../index.md)/[com.trustless.requests.identity](index.md)

# Package-level declarations

## Types

| Name | Summary |
|---|---|
| [StaqRegisterUser2FAResponse](-staq-register-user2-f-a-response/index.md) | [kotlin]<br>@Serializable<br>data class [StaqRegisterUser2FAResponse](-staq-register-user2-f-a-response/index.md)(val token: [StaqUserTokenResponse](-staq-user-token-response/index.md)) |
| [StaqRegisterUserResponse](-staq-register-user-response/index.md) | [kotlin]<br>@Serializable<br>data class [StaqRegisterUserResponse](-staq-register-user-response/index.md)(val username: String, val id: String, val phoneNumber: String? = null, val email: String, val lastName: String? = null, val firstName: String? = null) |
| [StaqRetrieveUserResponse](-staq-retrieve-user-response/index.md) | [kotlin]<br>@Serializable<br>data class [StaqRetrieveUserResponse](-staq-retrieve-user-response/index.md)(val username: String, val email: String, val firstName: String, val lastName: String, val phoneNumber: String) |
| [StaqTokenResponse](-staq-token-response/index.md) | [kotlin]<br>@Serializable<br>data class [StaqTokenResponse](-staq-token-response/index.md)(val accessToken: String, val tokenType: String, val expiresIn: Int, val scope: String) |
| [StaqUserTokenResponse](-staq-user-token-response/index.md) | [kotlin]<br>@Serializable<br>data class [StaqUserTokenResponse](-staq-user-token-response/index.md)(val accessToken: String, val tokenType: String, val expiresIn: Int, val scope: String, val refreshToken: String, val refreshExpiresIn: Int) |
