//[trustless](../../../index.md)/[com.trustless](../index.md)/[TrustlessSDK](index.md)/[getCardTransactions](get-card-transactions.md)

# getCardTransactions

[kotlin]\
suspend fun [getCardTransactions](get-card-transactions.md)(token: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), dateFrom: [Date](https://developer.android.com/reference/kotlin/java/util/Date.html), dateTo: [Date](https://developer.android.com/reference/kotlin/java/util/Date.html) = Date()): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[StaqCardTransaction](../../com.trustless.requests.cards/-staq-card-transaction/index.md)&gt;

Retrieves all transactions for the card

[Server Api Reference](https://developer.staq.io/docs/apis/cards#/V1/List%20all%20transactions)

#### Parameters

kotlin

| | |
|---|---|
| token | The token of the card returned when card was issued |
| dateFrom | From Date |
| dateTo | To Date |
