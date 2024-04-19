//[trustless](../../../index.md)/[com.trustless.providers](../index.md)/[AccountsProvider](index.md)

# AccountsProvider

interface [AccountsProvider](index.md)

#### Inheritors

| |
|---|
| [AccountsProviderImp](../../com.trustless.providers.implementations/-accounts-provider-imp/index.md) |

## Functions

| Name | Summary |
|---|---|
| [createAnAccount](create-an-account.md) | [kotlin]<br>abstract suspend fun [createAnAccount](create-an-account.md)(params: [CreateAnAccountParams](../../com.trustless.requests.accounts.createAnAccount/-create-an-account-params/index.md)): [StaqAccountResponse](../../com.trustless.requests.accounts/-staq-account-response/index.md)<br>Opens a new account for the customer |
| [deleteAccountByNumber](delete-account-by-number.md) | [kotlin]<br>abstract suspend fun [deleteAccountByNumber](delete-account-by-number.md)(accountNumber: String, accountNumberTransferMoneyTo: String? = null)<br>Closes the customer's bank account |
| [getAccountByNumber](get-account-by-number.md) | [kotlin]<br>abstract suspend fun [getAccountByNumber](get-account-by-number.md)(accountNumber: String): [StaqAccountResponse](../../com.trustless.requests.accounts/-staq-account-response/index.md)<br>Returns details of the customer's bank account |
| [getAccounts](get-accounts.md) | [kotlin]<br>abstract fun [getAccounts](get-accounts.md)(pageSize: Int, currentPage: Int = 1): [Paginator](../../com.trustless.paginator/-paginator/index.md)&lt;[StaqAccountResponse](../../com.trustless.requests.accounts/-staq-account-response/index.md)&gt;<br>Returns all accounts for the specified customer |
| [getAccountTransactions](get-account-transactions.md) | [kotlin]<br>abstract fun [getAccountTransactions](get-account-transactions.md)(pageSize: Int, currentPage: Int = 1, accountNumber: String, dateFrom: Date, dateTo: Date = Date()): [Paginator](../../com.trustless.paginator/-paginator/index.md)&lt;[StaqAccountTransaction](../../com.trustless.requests.accounts/-staq-account-transaction/index.md)&gt;<br>Returns all transactions for the specified account completed during the requested period |
