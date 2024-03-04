//[trustless](../../../index.md)/[com.trustless.providers](../index.md)/[TransfersProvider](index.md)

# TransfersProvider

interface [TransfersProvider](index.md)

#### Inheritors

| |
|---|
| [TransfersProviderImp](../../com.trustless.providers.implementations/-transfers-provider-imp/index.md) |

## Functions

| Name | Summary |
|---|---|
| [confirmTransfer](confirm-transfer.md) | [kotlin]<br>abstract suspend fun [confirmTransfer](confirm-transfer.md)(transferId: Int, documents: List&lt;File&gt;? = null): [StaqTransferResponse](../../com.trustless.requests.transfers/-staq-transfer-response/index.md) |
| [createCliqTransfer](create-cliq-transfer.md) | [kotlin]<br>abstract suspend fun [createCliqTransfer](create-cliq-transfer.md)(params: [CreateCliqTransferParams](../../com.trustless.requests.transfers/-create-cliq-transfer-params/index.md)): [StaqTransferResponse](../../com.trustless.requests.transfers/-staq-transfer-response/index.md)<br>Creates a new Cliq transfer and returns fees information |
| [createInternalTransfer](create-internal-transfer.md) | [kotlin]<br>abstract suspend fun [createInternalTransfer](create-internal-transfer.md)(params: [CreateInternalTransferParams](../../com.trustless.requests.transfers/-create-internal-transfer-params/index.md)): [StaqTransferResponse](../../com.trustless.requests.transfers/-staq-transfer-response/index.md)<br>Creates a new internal transfer and returns fees information |
| [getTransferById](get-transfer-by-id.md) | [kotlin]<br>abstract suspend fun [getTransferById](get-transfer-by-id.md)(transferId: Int): [StaqTransferResponse](../../com.trustless.requests.transfers/-staq-transfer-response/index.md)<br>Retrieves details on the single transfer identified by transferId |
| [getTransfers](get-transfers.md) | [kotlin]<br>abstract fun [getTransfers](get-transfers.md)(pageSize: Int, currentPage: Int = 1, type: String? = null, month: Int? = null, year: Int? = null): [Paginator](../../com.trustless.paginator/-paginator/index.md)&lt;[StaqTransferResponse](../../com.trustless.requests.transfers/-staq-transfer-response/index.md)&gt;<br>Retrieves all transfers submitted by a customer |
