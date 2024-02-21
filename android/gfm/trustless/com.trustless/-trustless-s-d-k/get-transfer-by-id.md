//[trustless](../../../index.md)/[com.trustless](../index.md)/[TrustlessSDK](index.md)/[getTransferById](get-transfer-by-id.md)

# getTransferById

[kotlin]\
suspend fun [getTransferById](get-transfer-by-id.md)(transferId: Int): [StaqTransferResponse](../../com.trustless.requests.transfers/-staq-transfer-response/index.md)

Retrieves details on the single transfer identified by transferId

[Server Api Reference](https://developer.staq.io/docs/apis/transfers#/Transfers/Get%20a%20transfer%20details)

#### Parameters

kotlin

| | |
|---|---|
| transferId | The unique identifier of the transfer |

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
