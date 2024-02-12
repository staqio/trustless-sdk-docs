//[trustless](../../../index.md)/[com.trustless](../index.md)/[TrustlessSDK](index.md)/[getAccountTransactions](get-account-transactions.md)

# getAccountTransactions

[kotlin]\
fun [getAccountTransactions](get-account-transactions.md)(pageSize: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), currentPage: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 1, accountNumber: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), dateFrom: [Date](https://developer.android.com/reference/kotlin/java/util/Date.html), dateTo: [Date](https://developer.android.com/reference/kotlin/java/util/Date.html) = Date()): [Paginator](../../com.trustless.paginator/-paginator/index.md)&lt;[StaqAccountTransaction](../../com.trustless.requests.accounts/-staq-account-transaction/index.md)&gt;

Returns all transactions for the specified account completed during the requested period

[Server Api Reference](https://developer.staq.io/docs/apis/accounts#/Accounts/List%20all%20transactions)

#### Parameters

kotlin

| | |
|---|---|
| pageSize | The number of items for page |
| currentPage | The number of page, the count starts from 1. |
| accountNumber | Bank account number of the customer |
| dateFrom | Date from (not required, empty value equals missing value) |
| dateTo | Date to (not required, empty value equals missing value) |
