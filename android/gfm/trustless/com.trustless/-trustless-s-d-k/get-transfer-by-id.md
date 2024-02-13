//[trustless](../../../index.md)/[com.trustless](../index.md)/[TrustlessSDK](index.md)/[getTransferById](get-transfer-by-id.md)

# getTransferById

[kotlin]\
suspend fun [getTransferById](get-transfer-by-id.md)(transferId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [StaqTransferResponse](../../com.trustless.requests.transfers/-staq-transfer-response/index.md)

Retrieves details on the single transfer identified by transferId

[Server Api Reference](https://developer.staq.io/docs/apis/transfers#/Transfers/Get%20a%20transfer%20details)

#### Parameters

kotlin

| | |
|---|---|
| transferId | The unique identifier of the transfer |

#### Throws

| | |
|---|---|
| [TrustlessException](../../com.trustless.exceptions/-trustless-exception/index.md) | Is thrown when the server returns custom error, or when error was not expected by the SDK |
| [TrustlessUserTokenExpiredException](../../com.trustless.exceptions/-trustless-user-token-expired-exception/index.md) | Is thrown when the token expires, either due to time period or server forced expiration |
| [TrustlessMalformedResponse](../../com.trustless.exceptions/-trustless-malformed-response/index.md) | Is thrown when server returned unexpected format of the data |
| CancellationException | Is thrown usually when the developer cancels the coroutine |
