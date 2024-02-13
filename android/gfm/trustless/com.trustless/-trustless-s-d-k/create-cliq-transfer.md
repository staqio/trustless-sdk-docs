//[trustless](../../../index.md)/[com.trustless](../index.md)/[TrustlessSDK](index.md)/[createCliqTransfer](create-cliq-transfer.md)

# createCliqTransfer

[kotlin]\
suspend fun [createCliqTransfer](create-cliq-transfer.md)(params: [CreateCliqTransferParams](../../com.trustless.requests.transfers/-create-cliq-transfer-params/index.md)): [StaqTransferResponse](../../com.trustless.requests.transfers/-staq-transfer-response/index.md)

Creates a new Cliq transfer and returns fees information

[Server Api Reference](https://developer.staq.io/docs/apis/transfers#/Transfers/Create%20a%20Cliq%20transfer)

#### Parameters

kotlin

| | |
|---|---|
| params | Create Cliq Transfer Params |

#### Throws

| | |
|---|---|
| [TrustlessException](../../com.trustless.exceptions/-trustless-exception/index.md) | Is thrown when the server returns custom error, or when error was not expected by the SDK |
| [TrustlessUserTokenExpiredException](../../com.trustless.exceptions/-trustless-user-token-expired-exception/index.md) | Is thrown when the token expires, either due to time period or server forced expiration |
| [TrustlessMalformedResponse](../../com.trustless.exceptions/-trustless-malformed-response/index.md) | Is thrown when server returned unexpected format of the data |
| CancellationException | Is thrown usually when the developer cancels the coroutine |
