//[trustless](../../../index.md)/[com.trustless.providers.implementations](../index.md)/[TransfersProviderImp](index.md)/[getTransfers](get-transfers.md)

# getTransfers

[kotlin]\
open override fun [getTransfers](get-transfers.md)(pageSize: Int, currentPage: Int, type: String?, month: Int?, year: Int?): [Paginator](../../com.trustless.paginator/-paginator/index.md)&lt;[StaqTransferResponse](../../com.trustless.requests.transfers/-staq-transfer-response/index.md)&gt;

Retrieves all transfers submitted by a customer

#### Parameters

kotlin

| | |
|---|---|
| pageSize | the size of the page |
| currentPage | the starting page, the count starts from 1. |
| type | Type of transfer Example : ALL, Standing, Saved, Transfer, Goal |
| month | Month filter for transfer the integer should be between 1 and 12. |
| year | Year filter for transfer |
