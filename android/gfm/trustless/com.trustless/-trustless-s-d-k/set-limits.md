//[trustless](../../../index.md)/[com.trustless](../index.md)/[TrustlessSDK](index.md)/[setLimits](set-limits.md)

# setLimits

[kotlin]\
suspend fun [setLimits](set-limits.md)(token: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), params: [SetLimitsParams](../../com.trustless.requests.cards.setLimits/-set-limits-params/index.md)): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[StaqSetLimitResponse](../../com.trustless.requests.cards/-staq-set-limit-response/index.md)&gt;

Sets a card spending limits

[Server Api Reference](https://developer.staq.io/docs/apis/cards#/Limits/Set%20a%20card%20spending%20limits)

#### Parameters

kotlin

| | |
|---|---|
| token | The token of the card returned when card was issued |
| params | set limit params |

#### Throws

| | |
|---|---|
| [TrustlessException](../../com.trustless.exceptions/-trustless-exception/index.md) | Is thrown when the server returns custom error, or when error was not expected by the SDK |
| [TrustlessUserTokenExpiredException](../../com.trustless.exceptions/-trustless-user-token-expired-exception/index.md) | Is thrown when the token expires, either due to time period or server forced expiration |
| [TrustlessMalformedResponse](../../com.trustless.exceptions/-trustless-malformed-response/index.md) | Is thrown when server returned unexpected format of the data |
| CancellationException | Is thrown usually when the developer cancels the coroutine |
