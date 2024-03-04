//[trustless](../../../index.md)/[com.trustless.providers.implementations](../index.md)/[KYCProviderImp](index.md)/[uploadKyc](upload-kyc.md)

# uploadKyc

[kotlin]\
open suspend override fun [uploadKyc](upload-kyc.md)(body: String, documents: Map&lt;String, File&gt;): [CreateKycResponse](../../com.trustless.requests.kyc.createKyc/-create-kyc-response/index.md)

Uploads KYC documents

#### Parameters

kotlin

| | |
|---|---|
| body | you can get body by using this function [com.trustless.requests.kyc.retrieveSteps.steps.KYCStepsManager.getJSON](../../com.trustless.requests.kyc.retrieveSteps.steps/-k-y-c-steps-manager/get-j-s-o-n.md) |
| documents | you can get documents by using this function [com.trustless.requests.kyc.retrieveSteps.steps.KYCStepsManager.getDocumentsMap](../../com.trustless.requests.kyc.retrieveSteps.steps/-k-y-c-steps-manager/get-documents-map.md) For more information refer to KYC section in the documentation or to [com.trustless.requests.kyc.retrieveSteps.steps.KYCStepsManager](../../com.trustless.requests.kyc.retrieveSteps.steps/-k-y-c-steps-manager/index.md) |

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
