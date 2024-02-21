//[trustless](../../../index.md)/[com.trustless](../index.md)/[TrustlessSDK](index.md)/[getCards](get-cards.md)

# getCards

[kotlin]\
fun [getCards](get-cards.md)(pageSize: Int, currentPage: Int = 1): [Paginator](../../com.trustless.paginator/-paginator/index.md)&lt;[StaqCardDetails](../../com.trustless.requests.cards/-staq-card-details/index.md)&gt;

Creates a new virtual prepaid card. Afer card is created, you can retrieve sensitive card information (e.g. Pan. Cvv) later using /pan API endpoint.

[Server Api Reference](https://developer.staq.io/docs/apis/cards#/Cards/Create%20card.%20V2)

#### Parameters

kotlin

| | |
|---|---|
| pageSize | the size of the page |
| currentPage | the starting page, the count starts from 1. |
