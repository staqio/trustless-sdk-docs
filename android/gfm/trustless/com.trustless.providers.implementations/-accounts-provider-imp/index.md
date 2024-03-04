//[trustless](../../../index.md)/[com.trustless.providers.implementations](../index.md)/[AccountsProviderImp](index.md)

# AccountsProviderImp

[kotlin]\
class [AccountsProviderImp](index.md) : [AccountsProvider](../../com.trustless.providers/-accounts-provider/index.md)

## Functions

| Name | Summary |
|---|---|
| [createAnAccount](create-an-account.md) | [kotlin]<br>open suspend override fun [createAnAccount](create-an-account.md)(params: [CreateAnAccountParams](../../com.trustless.requests.accounts.createAnAccount/-create-an-account-params/index.md)): [StaqAccountResponse](../../com.trustless.requests.accounts/-staq-account-response/index.md)<br>Opens a new account for the customer |
| [deleteAccountByNumber](delete-account-by-number.md) | [kotlin]<br>open suspend override fun [deleteAccountByNumber](delete-account-by-number.md)(accountNumber: String, accountNumberTransferMoneyTo: String?)<br>Closes the customer's bank account |
| [getAccountByNumber](get-account-by-number.md) | [kotlin]<br>open suspend override fun [getAccountByNumber](get-account-by-number.md)(accountNumber: String): [StaqAccountResponse](../../com.trustless.requests.accounts/-staq-account-response/index.md)<br>Returns details of the customer's bank account |
| [getAccounts](get-accounts.md) | [kotlin]<br>open override fun [getAccounts](get-accounts.md)(pageSize: Int, currentPage: Int): [Paginator](../../com.trustless.paginator/-paginator/index.md)&lt;[StaqAccountResponse](../../com.trustless.requests.accounts/-staq-account-response/index.md)&gt;<br>Returns all accounts for the specified customer |
| [getAccountTransactions](get-account-transactions.md) | [kotlin]<br>open override fun [getAccountTransactions](get-account-transactions.md)(pageSize: Int, currentPage: Int, accountNumber: String, dateFrom: Date, dateTo: Date): [Paginator](../../com.trustless.paginator/-paginator/index.md)&lt;[StaqAccountTransaction](../../com.trustless.requests.accounts/-staq-account-transaction/index.md)&gt;<br>Returns all transactions for the specified account completed during the requested period |
