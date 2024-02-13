//[trustless](../../../index.md)/[com.trustless](../index.md)/[TrustlessSDK](index.md)/[getWithdrawFromCardRequest](get-withdraw-from-card-request.md)

# getWithdrawFromCardRequest

[kotlin]\
fun [getWithdrawFromCardRequest](get-withdraw-from-card-request.md)(token: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [WithdrawFromCardRequest](../../com.trustless.requests.cards.withdraw/-withdraw-from-card-request/index.md)

Debit funds from a card to the customer's account

[Server Api Reference](https://developer.staq.io/docs/apis/cards#/Cards/Debit%20funds)

#### Return

[WithdrawFromCardRequest](../../com.trustless.requests.cards.withdraw/-withdraw-from-card-request/index.md) request class to handle request.

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
