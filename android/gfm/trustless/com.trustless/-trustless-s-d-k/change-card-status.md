//[trustless](../../../index.md)/[com.trustless](../index.md)/[TrustlessSDK](index.md)/[changeCardStatus](change-card-status.md)

# changeCardStatus

[kotlin]\
suspend fun [changeCardStatus](change-card-status.md)(token: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), status: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [StaqChangeCardStatusResponse](../../com.trustless.requests.cards/-staq-change-card-status-response/index.md)

The method allows managing the card status

[Server Api Reference](https://developer.staq.io/docs/apis/cards#/Cards/Set%20status)

#### Parameters

kotlin

| | |
|---|---|
| token | The token of the card returned when card was issued |
| status | Status to be assigned to the card ENUM:  ACTIVATED, FROZEN, CLOSED |

#### Throws

| | |
|---|---|
| [TrustlessException](../../com.trustless.exceptions/-trustless-exception/index.md) | Is thrown when the server returns custom error, or when error was not expected by the SDK |
| [TrustlessUserTokenExpiredException](../../com.trustless.exceptions/-trustless-user-token-expired-exception/index.md) | Is thrown when the token expires, either due to time period or server forced expiration |
| [TrustlessMalformedResponse](../../com.trustless.exceptions/-trustless-malformed-response/index.md) | Is thrown when server returned unexpected format of the data |
| CancellationException | Is thrown usually when the developer cancels the coroutine |
