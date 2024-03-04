//[trustless](../../../index.md)/[com.trustless.providers.implementations](../index.md)/[CardsProviderImp](index.md)/[getCards](get-cards.md)

# getCards

[kotlin]\
open override fun [getCards](get-cards.md)(pageSize: Int, currentPage: Int): [Paginator](../../com.trustless.paginator/-paginator/index.md)&lt;[StaqCardDetails](../../com.trustless.requests.cards/-staq-card-details/index.md)&gt;

Creates a new virtual prepaid card. Afer card is created, you can retrieve sensitive card information (e.g. Pan. Cvv) later using /pan API endpoint.

#### Parameters

kotlin

| | |
|---|---|
| pageSize | the size of the page |
| currentPage | the starting page, the count starts from 1. |
