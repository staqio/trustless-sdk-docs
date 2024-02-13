//[trustless](../../../index.md)/[com.trustless](../index.md)/[TrustlessSDK](index.md)/[createAnAccount](create-an-account.md)

# createAnAccount

[kotlin]\
suspend fun [createAnAccount](create-an-account.md)(params: [CreateAnAccountParams](../../com.trustless.requests.accounts.createAnAccount/-create-an-account-params/index.md)): [StaqAccountResponse](../../com.trustless.requests.accounts/-staq-account-response/index.md)

Opens a new account for the customer

[Server Api Reference](https://developer.staq.io/docs/apis/accounts#/Accounts/Create%20an%20account)

#### Parameters

kotlin

| | |
|---|---|
| params | params to create an account |

#### Throws

| | |
|---|---|
| [TrustlessException](../../com.trustless.exceptions/-trustless-exception/index.md) | Is thrown when the server returns custom error, or when error was not expected by the SDK |
| [TrustlessUserTokenExpiredException](../../com.trustless.exceptions/-trustless-user-token-expired-exception/index.md) | Is thrown when the token expires, either due to time period or server forced expiration |
| [TrustlessMalformedResponse](../../com.trustless.exceptions/-trustless-malformed-response/index.md) | Is thrown when server returned unexpected format of the data |
| CancellationException | Is thrown usually when the developer cancels the coroutine |
