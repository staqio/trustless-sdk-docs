//[trustless](../../../index.md)/[com.trustless](../index.md)/[TrustlessSDK](index.md)/[retrieveCustomerId](retrieve-customer-id.md)

# retrieveCustomerId

[kotlin]\
suspend fun [retrieveCustomerId](retrieve-customer-id.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)

[Server Api Reference](https://developer.finto.io/docs/apis/kyc#/Customers/Get%20Customer%20Status)

Fetches the customer's unique identifier, prioritizing a cached version for efficiency. If the ID is not available in the cache, it initiates a server request to obtain it.

#### Return

Customer id