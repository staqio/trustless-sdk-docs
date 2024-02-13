//[trustless](../../../index.md)/[com.trustless](../index.md)/[TrustlessSDK](index.md)/[changeCardMobileNumber](change-card-mobile-number.md)

# changeCardMobileNumber

[kotlin]\
suspend fun [changeCardMobileNumber](change-card-mobile-number.md)(token: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), mobile: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [StaqChangeMobileNumberResponse](../../com.trustless.requests.cards/-staq-change-mobile-number-response/index.md)

Updates mobile phone number for 3DS

[Server Api Reference](https://developer.staq.io/docs/apis/cards#/Cards/Set%20a%20mobile%20number)

#### Parameters

kotlin

| | |
|---|---|
| token | The token of the card returned when card was issued |
| mobile | Cardholder's mobile number. Should start from a single 0 (zero), no + (plus) sign is allowed. MAXLENGTH: 15 MINLENGTH: 4 PATTERN: ^0?1-9+0-9*$ |

#### Throws

| |
|---|
| [TrustlessMobileNumberException](../../com.trustless.exceptions/-trustless-mobile-number-exception/index.md) |
| [TrustlessException](../../com.trustless.exceptions/-trustless-exception/index.md) | Is thrown when the server returns custom error, or when error was not expected by the SDK |
| [TrustlessUserTokenExpiredException](../../com.trustless.exceptions/-trustless-user-token-expired-exception/index.md) | Is thrown when the token expires, either due to time period or server forced expiration |
| [TrustlessMalformedResponse](../../com.trustless.exceptions/-trustless-malformed-response/index.md) | Is thrown when server returned unexpected format of the data |
| CancellationException | Is thrown usually when the developer cancels the coroutine |
