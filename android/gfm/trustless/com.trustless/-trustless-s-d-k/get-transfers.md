//[trustless](../../../index.md)/[com.trustless](../index.md)/[TrustlessSDK](index.md)/[getTransfers](get-transfers.md)

# getTransfers

[kotlin]\
fun [getTransfers](get-transfers.md)(pageSize: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), currentPage: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 1, type: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, month: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)? = null, year: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)? = null): [Paginator](../../com.trustless.paginator/-paginator/index.md)&lt;[StaqTransferResponse](../../com.trustless.requests.transfers/-staq-transfer-response/index.md)&gt;

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
