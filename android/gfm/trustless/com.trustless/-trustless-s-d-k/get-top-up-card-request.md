//[trustless](../../../index.md)/[com.trustless](../index.md)/[TrustlessSDK](index.md)/[getTopUpCardRequest](get-top-up-card-request.md)

# getTopUpCardRequest

[kotlin]\
fun [getTopUpCardRequest](get-top-up-card-request.md)(token: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [TopUpCardRequest](../../com.trustless.requests.cards.topUp/-top-up-card-request/index.md)

Credits funds to a card from the customer's account

[Server Api Reference](https://developer.staq.io/docs/apis/cards#/Cards/Credit%20funds)

#### Return

[TopUpCardRequest](../../com.trustless.requests.cards.topUp/-top-up-card-request/index.md) request class to handle request.

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
