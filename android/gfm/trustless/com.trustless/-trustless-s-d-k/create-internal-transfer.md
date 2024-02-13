//[trustless](../../../index.md)/[com.trustless](../index.md)/[TrustlessSDK](index.md)/[createInternalTransfer](create-internal-transfer.md)

# createInternalTransfer

[kotlin]\
suspend fun [createInternalTransfer](create-internal-transfer.md)(params: [CreateInternalTransferParams](../../com.trustless.requests.transfers/-create-internal-transfer-params/index.md)): [StaqTransferResponse](../../com.trustless.requests.transfers/-staq-transfer-response/index.md)

Creates a new internal transfer and returns fees information

[Server Api Reference](https://developer.staq.io/docs/apis/transfers#/Transfers/Create%20an%20internal%20transfer)

#### Parameters

kotlin

| | |
|---|---|
| params | params to create internal transfer |

#### Throws

| | |
|---|---|
| [TrustlessException](../../com.trustless.exceptions/-trustless-exception/index.md) | Is thrown when the server returns custom error, or when error was not expected by the SDK |
| [TrustlessUserTokenExpiredException](../../com.trustless.exceptions/-trustless-user-token-expired-exception/index.md) | Is thrown when the token expires, either due to time period or server forced expiration |
| [TrustlessMalformedResponse](../../com.trustless.exceptions/-trustless-malformed-response/index.md) | Is thrown when server returned unexpected format of the data |
| CancellationException | Is thrown usually when the developer cancels the coroutine |
