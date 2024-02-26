//[trustless](../../../index.md)/[com.trustless.providers](../index.md)/[KYCProvider](index.md)

# KYCProvider

[kotlin]\
class [KYCProvider](index.md)

## Functions

| Name | Summary |
|---|---|
| [getCityList](get-city-list.md) | [kotlin]<br>suspend fun [getCityList](get-city-list.md)(countryCode: String): [RetrieveQuestionsResponse](../../com.trustless.requests.kyc.retrieveQuestions/-retrieve-questions-response/index.md)<br>Retrieves list of values defined by URI parameter {listname} and optionally filtered by the value of the query parameter {filtervalue} |
| [getSteps](get-steps.md) | [kotlin]<br>suspend fun [getSteps](get-steps.md)(sourceFields: [SourceFieldsMap](../../com.trustless.requests.kyc.retrieveSteps.steps/-source-fields-map/index.md)): [KYCStepsManager](../../com.trustless.requests.kyc.retrieveSteps.steps/-k-y-c-steps-manager/index.md)<br>Retrieves JSON descriptor of the data that should be collected by partner application and submitted to initiate KYC |
| [retrieveCustomerId](retrieve-customer-id.md) | [kotlin]<br>suspend fun [retrieveCustomerId](retrieve-customer-id.md)(): String<br>Fetches the customer's unique identifier, prioritizing a cached version for efficiency. If the ID is not available in the cache, it initiates a server request to obtain it. |
| [retrieveKycId](retrieve-kyc-id.md) | [kotlin]<br>suspend fun [retrieveKycId](retrieve-kyc-id.md)(): String<br>Retrieve KYC Id |
| [uploadKyc](upload-kyc.md) | [kotlin]<br>suspend fun [uploadKyc](upload-kyc.md)(body: String, documents: Map&lt;String, File&gt;): [CreateKycResponse](../../com.trustless.requests.kyc.createKyc/-create-kyc-response/index.md)<br>Uploads KYC documents |
