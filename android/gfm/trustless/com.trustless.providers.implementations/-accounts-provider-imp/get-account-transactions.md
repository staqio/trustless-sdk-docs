//[trustless](../../../index.md)/[com.trustless.providers.implementations](../index.md)/[AccountsProviderImp](index.md)/[getAccountTransactions](get-account-transactions.md)

# getAccountTransactions

[kotlin]\
open override fun [getAccountTransactions](get-account-transactions.md)(pageSize: Int, currentPage: Int, accountNumber: String, dateFrom: Date, dateTo: Date): [Paginator](../../com.trustless.paginator/-paginator/index.md)&lt;[StaqAccountTransaction](../../com.trustless.requests.accounts/-staq-account-transaction/index.md)&gt;

Returns all transactions for the specified account completed during the requested period

#### Parameters

kotlin

| | |
|---|---|
| pageSize | The number of items for page |
| currentPage | The number of page, the count starts from 1. |
| accountNumber | Bank account number of the customer |
| dateFrom | Date from (not required, empty value equals missing value) |
| dateTo | Date to (not required, empty value equals missing value) |
