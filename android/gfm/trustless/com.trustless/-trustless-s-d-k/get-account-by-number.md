//[trustless](../../../index.md)/[com.trustless](../index.md)/[TrustlessSDK](index.md)/[getAccountByNumber](get-account-by-number.md)

# getAccountByNumber

[kotlin]\
suspend fun [getAccountByNumber](get-account-by-number.md)(accountNumber: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [StaqAccountResponse](../../com.trustless.requests.accounts/-staq-account-response/index.md)

Returns details of the customer's bank account

[Server Api Reference](https://developer.staq.io/docs/apis/accounts#/Accounts/Get%20an%20account)

#### Parameters

kotlin

| | |
|---|---|
| accountNumber | Bank account number of the customer |

#### Throws

| | |
|---|---|
| [TrustlessException](../../com.trustless.exceptions/-trustless-exception/index.md) | Is thrown when the server returns custom error, or when error was not expected by the SDK |
| [TrustlessUserTokenExpiredException](../../com.trustless.exceptions/-trustless-user-token-expired-exception/index.md) | Is thrown when the token expires, either due to time period or server forced expiration |
| [TrustlessMalformedResponse](../../com.trustless.exceptions/-trustless-malformed-response/index.md) | Is thrown when server returned unexpected format of the data |
| CancellationException | Is thrown usually when the developer cancels the coroutine |
