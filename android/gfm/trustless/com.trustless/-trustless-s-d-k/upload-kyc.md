//[trustless](../../../index.md)/[com.trustless](../index.md)/[TrustlessSDK](index.md)/[uploadKyc](upload-kyc.md)

# uploadKyc

[kotlin]\
suspend fun [uploadKyc](upload-kyc.md)(body: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), documents: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [File](https://developer.android.com/reference/kotlin/java/io/File.html)&gt;): [CreateKycResponse](../../com.trustless.requests.kyc.createKyc/-create-kyc-response/index.md)

Uploads KYC documents

[Server Api Reference](https://developer.staq.io/docs/apis/kyc#/Customers/Create%20a%20KYC)

#### Parameters

kotlin

| | |
|---|---|
| body | you can get body by using this function [com.trustless.requests.kyc.retrieveSteps.steps.AllKYCSteps.getJSON](../../com.trustless.requests.kyc.retrieveSteps.steps/-all-k-y-c-steps/get-j-s-o-n.md) |
| documents | you can get documents by using this function [com.trustless.requests.kyc.retrieveSteps.steps.AllKYCSteps.getDocumentsMap](../../com.trustless.requests.kyc.retrieveSteps.steps/-all-k-y-c-steps/get-documents-map.md) For more information refer to KYC section in the documentation or to [com.trustless.requests.kyc.retrieveSteps.steps.AllKYCSteps](../../com.trustless.requests.kyc.retrieveSteps.steps/-all-k-y-c-steps/index.md) |

#### Throws

| | |
|---|---|
| [TrustlessException](../../com.trustless.exceptions/-trustless-exception/index.md) | Is thrown when the server returns custom error, or when error was not expected by the SDK |
| [TrustlessUserTokenExpiredException](../../com.trustless.exceptions/-trustless-user-token-expired-exception/index.md) | Is thrown when the token expires, either due to time period or server forced expiration |
| [TrustlessMalformedResponse](../../com.trustless.exceptions/-trustless-malformed-response/index.md) | Is thrown when server returned unexpected format of the data |
| CancellationException | Is thrown usually when the developer cancels the coroutine |
