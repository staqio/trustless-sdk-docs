//[trustless](../../../index.md)/[com.trustless](../index.md)/[TrustlessSDK](index.md)/[changeCardMobileNumber](change-card-mobile-number.md)

# changeCardMobileNumber

[kotlin]\
suspend fun [changeCardMobileNumber](change-card-mobile-number.md)(token: String, mobile: String): [StaqChangeMobileNumberResponse](../../com.trustless.requests.cards/-staq-change-mobile-number-response/index.md)

Updates mobile phone number for 3DS

[Server Api Reference](https://developer.staq.io/docs/apis/cards#/Cards/Set%20a%20mobile%20number)

#### Parameters

kotlin

| | |
|---|---|
| token | The token of the card returned when card was issued |
| mobile | Cardholder's mobile number. Should start from a single 0 (zero), no + (plus) sign is allowed. MAXLENGTH: 15 MINLENGTH: 4 PATTERN: ^0?1-9+0-9*$ |

#### Throws

| |
|---|
| [TrustlessMobileNumberException](../../com.trustless.exceptions/-trustless-mobile-number-exception/index.md) |
| [TrustlessException](../../com.trustless.exceptions/-trustless-exception/index.md) | Is thrown when the server returns custom error, or when error was not expected by the SDK |
| [TrustlessUserTokenExpiredException](../../com.trustless.exceptions/-trustless-user-token-expired-exception/index.md) | Is thrown when the token expires, either due to time period or server forced expiration |
| [TrustlessMalformedResponse](../../com.trustless.exceptions/-trustless-malformed-response/index.md) | Is thrown when server returned unexpected format of the data |
| [TrustlessExceptionListener](../../com.trustless.exceptions/-trustless-exception-listener/index.md) | Is thrown when developer has not set security listener |
| [TrustlessExceptionSecurityProviderIsNotInstalled](../../com.trustless.exceptions/-trustless-exception-security-provider-is-not-installed/index.md) | Is thrown when user's device doesn't have a security provider |
| CancellationException | Is thrown usually when the developer cancels the coroutine |
| [TrustlessNotInitializedSdkException](../../com.trustless.exceptions/-trustless-not-initialized-sdk-exception/index.md) | Is thrown when trying to access this method while sdk is not initialized |
| [TrustlessCustomerIdIsNull](../../com.trustless.exceptions/-trustless-customer-id-is-null/index.md) | Is thrown when customer id is required for a request but customer id is null |
| [TrustlessKycIdIsNull](../../com.trustless.exceptions/-trustless-kyc-id-is-null/index.md) | Is thrown when kyc id is required for a request but kyc id is null |