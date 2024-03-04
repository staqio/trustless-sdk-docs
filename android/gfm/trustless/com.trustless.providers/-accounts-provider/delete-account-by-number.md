//[trustless](../../../index.md)/[com.trustless.providers](../index.md)/[AccountsProvider](index.md)/[deleteAccountByNumber](delete-account-by-number.md)

# deleteAccountByNumber

[kotlin]\
abstract suspend fun [deleteAccountByNumber](delete-account-by-number.md)(accountNumber: String, accountNumberTransferMoneyTo: String? = null)

Closes the customer's bank account

#### Parameters

kotlin

| | |
|---|---|
| accountNumber | The token of the card returned when card was issued |
| accountNumberTransferMoneyTo | Account number to credit funds available on the account to be closed |

#### Throws

| | |
|---|---|
| [TrustlessException](../../com.trustless.exceptions/-trustless-exception/index.md) | Is thrown when the server returns custom error, or when error was not expected by the SDK |
| [TrustlessUserTokenExpiredException](../../com.trustless.exceptions/-trustless-user-token-expired-exception/index.md) | Is thrown when the token expires, either due to time period or server forced expiration |
| [TrustlessMalformedResponse](../../com.trustless.exceptions/-trustless-malformed-response/index.md) | Is thrown when server returned unexpected format of the data |
| [TrustlessExceptionListener](../../com.trustless.exceptions/-trustless-exception-listener/index.md) | Is thrown when developer has not set security listener |
| [TrustlessExceptionSecurityProviderIsNotInstalled](../../com.trustless.exceptions/-trustless-exception-security-provider-is-not-installed/index.md) | Is thrown when user's device doesn't have a security provider |
| CancellationException | Is thrown usually when the developer cancels the coroutine |
| [TrustlessNotInitializedSdkException](../../com.trustless.exceptions/-trustless-not-initialized-sdk-exception/index.md) | Is thrown when trying to access this method while sdk is not initialized |
| [TrustlessCustomerIdIsNull](../../com.trustless.exceptions/-trustless-customer-id-is-null/index.md) | Is thrown when customer id is required for a request but customer id is null |
| [TrustlessKycIdIsNull](../../com.trustless.exceptions/-trustless-kyc-id-is-null/index.md) | Is thrown when kyc id is required for a request but kyc id is null |
