//[trustless](../../../index.md)/[com.trustless](../index.md)/[TrustlessSDK](index.md)/[getAccounts](get-accounts.md)

# getAccounts

[kotlin]\
fun [getAccounts](get-accounts.md)(pageSize: Int, currentPage: Int = 1): [Paginator](../../com.trustless.paginator/-paginator/index.md)&lt;[StaqAccountResponse](../../com.trustless.requests.accounts/-staq-account-response/index.md)&gt;

Returns all accounts for the specified customer

[Server Api Reference](https://developer.staq.io/docs/apis/accounts#/Accounts/List%20all%20customer's%20accounts)

#### Return

A [com.trustless.paginator.Paginator](../../com.trustless.paginator/-paginator/index.md) instance configured to manage the pagination of [com.trustless.requests.accounts.StaqAccountResponse](../../com.trustless.requests.accounts/-staq-account-response/index.md) objects.

#### Parameters

kotlin

| | |
|---|---|
| pageSize | the size of the page |
| currentPage | the starting page, the count starts from 1. |
