//[trustless](../../../index.md)/[com.trustless](../index.md)/[TrustlessSDK](index.md)/[getTransfers](get-transfers.md)

# getTransfers

[kotlin]\
fun [getTransfers](get-transfers.md)(pageSize: Int, currentPage: Int = 1, type: String? = null, month: Int? = null, year: Int? = null): [Paginator](../../com.trustless.paginator/-paginator/index.md)&lt;[StaqTransferResponse](../../com.trustless.requests.transfers/-staq-transfer-response/index.md)&gt;

Retrieves all transfers submitted by a customer

[Server Api Reference](https://developer.staq.io/docs/apis/transfers#/Transfers/List%20all%20transfers)

#### Parameters

kotlin

| | |
|---|---|
| pageSize | the size of the page |
| currentPage | the starting page, the count starts from 1. |
| type | Type of transfer Example : ALL, Standing, Saved, Transfer, Goal |
| month | Month filter for transfer the integer should be between 1 and 12. |
| year | Year filter for transfer |
