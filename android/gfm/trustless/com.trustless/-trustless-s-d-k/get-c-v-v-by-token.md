//[trustless](../../../index.md)/[com.trustless](../index.md)/[TrustlessSDK](index.md)/[getCVVByToken](get-c-v-v-by-token.md)

# getCVVByToken

[kotlin]\
suspend fun [getCVVByToken](get-c-v-v-by-token.md)(token: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [StaqGetCVVResponse](../../com.trustless.requests.cards/-staq-get-c-v-v-response/index.md)

Retrieves unmasked card PAN and CVV code

[Server Api Reference](https://developer.staq.io/docs/apis/cards#/Cards/Get%20PAN%2FCVV)

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
