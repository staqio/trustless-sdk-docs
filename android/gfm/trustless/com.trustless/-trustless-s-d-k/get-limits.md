//[trustless](../../../index.md)/[com.trustless](../index.md)/[TrustlessSDK](index.md)/[getLimits](get-limits.md)

# getLimits

[kotlin]\
suspend fun [getLimits](get-limits.md)(token: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [StaqGetLimitResponse](../../com.trustless.requests.cards/-staq-get-limit-response/index.md)

Retrieves all card spending limits

[Server Api Reference](https://developer.staq.io/docs/apis/cards#/Limits/Get%20a%20card%20spending%20limits)

#### Parameters

kotlin

| | |
|---|---|
| token | The token of the card returned when card was issued |

#### Throws

| | |
|---|---|
| [TrustlessException](../../com.trustless.exceptions/-trustless-exception/index.md) | Is thrown when the server returns custom error, or when error was not expected by the SDK |
| [TrustlessUserTokenExpiredException](../../com.trustless.exceptions/-trustless-user-token-expired-exception/index.md) | Is thrown when the token expires, either due to time period or server forced expiration |
| [TrustlessMalformedResponse](../../com.trustless.exceptions/-trustless-malformed-response/index.md) | Is thrown when server returned unexpected format of the data |
| CancellationException | Is thrown usually when the developer cancels the coroutine |
