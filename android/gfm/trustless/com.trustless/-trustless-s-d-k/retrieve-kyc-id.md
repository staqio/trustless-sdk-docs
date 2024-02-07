//[trustless](../../../index.md)/[com.trustless](../index.md)/[TrustlessSDK](index.md)/[retrieveKycId](retrieve-kyc-id.md)

# retrieveKycId

[kotlin]\
suspend fun [retrieveKycId](retrieve-kyc-id.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)

[Api Reference](https://developer.staq.io/docs/apis/kyc#/Customers/Get%20KYC%20Id) Fetches the kyc id, prioritizing a cached version for efficiency. If the ID is not available in the cache, it initiates a server request to obtain it.

#### Return

Kyc id
