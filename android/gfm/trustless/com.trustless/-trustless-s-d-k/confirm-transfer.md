//[trustless](../../../index.md)/[com.trustless](../index.md)/[TrustlessSDK](index.md)/[confirmTransfer](confirm-transfer.md)

# confirmTransfer

[kotlin]\
suspend fun [confirmTransfer](confirm-transfer.md)(transferId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), documents: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[File](https://developer.android.com/reference/kotlin/java/io/File.html)&gt;? = null): [StaqTransferResponse](../../com.trustless.requests.transfers/-staq-transfer-response/index.md)

[Server Api Reference](https://developer.staq.io/docs/apis/transfers#/Transfers/Confirm%20a%20transfer)

#### Parameters

kotlin

| | |
|---|---|
| transferId | The unique identifier of the transfer |
| documents | A list of documents required to complete the transfer. This list should align with the `requiredDocuments` field in the response object obtained when the transfer is created. |

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
