//[trustless](../../../index.md)/[com.trustless.paginator](../index.md)/[Paginator](index.md)/[fetchFirst](fetch-first.md)

# fetchFirst

[kotlin]\
abstract suspend fun [fetchFirst](fetch-first.md)(): [PaginatedResponse](../-paginated-response/index.md)&lt;List&lt;[T](index.md)&gt;&gt;

Fetches the first page of results and resets the internal page counter to 1, ensuring the pagination starts from the beginning.

#### Return

PaginatedResponse<List<T>> containing the data for the first page.

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
| [TrustlessPageNumberException](../../com.trustless.exceptions/-trustless-page-number-exception/index.md) | Is thrown when page number is out of range |
| [TrustlessPageSizeException](../../com.trustless.exceptions/-trustless-page-size-exception/index.md) | Is thrown when page size is out of range |
| [TrustlessCustomerIdIsNull](../../com.trustless.exceptions/-trustless-customer-id-is-null/index.md) | Is thrown when customer id is required for a request but customer id is null |
| [TrustlessKycIdIsNull](../../com.trustless.exceptions/-trustless-kyc-id-is-null/index.md) | Is thrown when kyc id is required for a request but kyc id is null |
