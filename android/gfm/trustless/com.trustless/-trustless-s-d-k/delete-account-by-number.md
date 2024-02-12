//[trustless](../../../index.md)/[com.trustless](../index.md)/[TrustlessSDK](index.md)/[deleteAccountByNumber](delete-account-by-number.md)

# deleteAccountByNumber

[kotlin]\
suspend fun [deleteAccountByNumber](delete-account-by-number.md)(accountNumber: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), accountNumberTransferMoneyTo: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null)

Closes the customer's bank account

[Server Api Reference](https://developer.staq.io/docs/apis/accounts#/Accounts/Close%20an%20account)

#### Parameters

kotlin

| | |
|---|---|
| accountNumber | The token of the card returned when card was issued |
| accountNumberTransferMoneyTo | Account number to credit funds available on the account to be closed |
