//[trustless](../../../index.md)/[com.trustless.providers.implementations](../index.md)/[TransfersProviderImp](index.md)

# TransfersProviderImp

[kotlin]\
class [TransfersProviderImp](index.md) : [TransfersProvider](../../com.trustless.providers/-transfers-provider/index.md)

## Functions

| Name | Summary |
|---|---|
| [confirmTransfer](confirm-transfer.md) | [kotlin]<br>open suspend override fun [confirmTransfer](confirm-transfer.md)(transferId: Int, documents: List&lt;File&gt;?): [StaqTransferResponse](../../com.trustless.requests.transfers/-staq-transfer-response/index.md) |
| [createCliqTransfer](create-cliq-transfer.md) | [kotlin]<br>open suspend override fun [createCliqTransfer](create-cliq-transfer.md)(params: [CreateCliqTransferParams](../../com.trustless.requests.transfers/-create-cliq-transfer-params/index.md)): [StaqTransferResponse](../../com.trustless.requests.transfers/-staq-transfer-response/index.md)<br>Creates a new Cliq transfer and returns fees information |
| [createInternalTransfer](create-internal-transfer.md) | [kotlin]<br>open suspend override fun [createInternalTransfer](create-internal-transfer.md)(params: [CreateInternalTransferParams](../../com.trustless.requests.transfers/-create-internal-transfer-params/index.md)): [StaqTransferResponse](../../com.trustless.requests.transfers/-staq-transfer-response/index.md)<br>Creates a new internal transfer and returns fees information |
| [getTransferById](get-transfer-by-id.md) | [kotlin]<br>open suspend override fun [getTransferById](get-transfer-by-id.md)(transferId: Int): [StaqTransferResponse](../../com.trustless.requests.transfers/-staq-transfer-response/index.md)<br>Retrieves details on the single transfer identified by transferId |
| [getTransfers](get-transfers.md) | [kotlin]<br>open override fun [getTransfers](get-transfers.md)(pageSize: Int, currentPage: Int, type: String?, month: Int?, year: Int?): [Paginator](../../com.trustless.paginator/-paginator/index.md)&lt;[StaqTransferResponse](../../com.trustless.requests.transfers/-staq-transfer-response/index.md)&gt;<br>Retrieves all transfers submitted by a customer |
