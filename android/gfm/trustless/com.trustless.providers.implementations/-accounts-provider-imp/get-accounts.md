//[trustless](../../../index.md)/[com.trustless.providers.implementations](../index.md)/[AccountsProviderImp](index.md)/[getAccounts](get-accounts.md)

# getAccounts

[kotlin]\
open override fun [getAccounts](get-accounts.md)(pageSize: Int, currentPage: Int): [Paginator](../../com.trustless.paginator/-paginator/index.md)&lt;[StaqAccountResponse](../../com.trustless.requests.accounts/-staq-account-response/index.md)&gt;

Returns all accounts for the specified customer

#### Return

A [com.trustless.paginator.Paginator](../../com.trustless.paginator/-paginator/index.md) instance configured to manage the pagination of [com.trustless.requests.accounts.StaqAccountResponse](../../com.trustless.requests.accounts/-staq-account-response/index.md) objects.

#### Parameters

kotlin

| | |
|---|---|
| pageSize | the size of the page |
| currentPage | the starting page, the count starts from 1. |
