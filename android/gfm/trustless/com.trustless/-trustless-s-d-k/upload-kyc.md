//[trustless](../../../index.md)/[com.trustless](../index.md)/[TrustlessSDK](index.md)/[uploadKyc](upload-kyc.md)

# uploadKyc

[kotlin]\
suspend fun [uploadKyc](upload-kyc.md)(body: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), documents: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [File](https://developer.android.com/reference/kotlin/java/io/File.html)&gt;): [CreateKycResponse](../../com.trustless.requests.kyc.createKyc/-create-kyc-response/index.md)

[Api Reference](https://developer.staq.io/docs/apis/kyc#/Customers/Create%20a%20KYC)

#### Parameters

kotlin

| | |
|---|---|
| body | you can get body by using this function [com.trustless.requests.kyc.retrieveSteps.steps.AllKYCSteps.getJSON](../../com.trustless.requests.kyc.retrieveSteps.steps/-all-k-y-c-steps/get-j-s-o-n.md) |
| documents | you can get documents by using this function [com.trustless.requests.kyc.retrieveSteps.steps.AllKYCSteps.getDocumentsMap](../../com.trustless.requests.kyc.retrieveSteps.steps/-all-k-y-c-steps/get-documents-map.md) For more information refer to KYC section in the documentation or to [com.trustless.requests.kyc.retrieveSteps.steps.AllKYCSteps](../../com.trustless.requests.kyc.retrieveSteps.steps/-all-k-y-c-steps/index.md) |
