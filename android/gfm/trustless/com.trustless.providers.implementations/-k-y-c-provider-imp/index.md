//[trustless](../../../index.md)/[com.trustless.providers.implementations](../index.md)/[KYCProviderImp](index.md)

# KYCProviderImp

[kotlin]\
class [KYCProviderImp](index.md) : [KYCProvider](../../com.trustless.providers/-k-y-c-provider/index.md)

## Functions

| Name | Summary |
|---|---|
| [getCityList](get-city-list.md) | [kotlin]<br>open suspend override fun [getCityList](get-city-list.md)(countryCode: String): [RetrieveQuestionsResponse](../../com.trustless.requests.kyc.retrieveQuestions/-retrieve-questions-response/index.md)<br>Retrieves list of values defined by URI parameter {listname} and optionally filtered by the value of the query parameter {filtervalue} |
| [getSteps](get-steps.md) | [kotlin]<br>open suspend override fun [getSteps](get-steps.md)(sourceFields: [SourceFieldsMap](../../com.trustless.requests.kyc.retrieveSteps.steps/-source-fields-map/index.md)): [KYCStepsManager](../../com.trustless.requests.kyc.retrieveSteps.steps/-k-y-c-steps-manager/index.md)<br>Retrieves JSON descriptor of the data that should be collected by partner application and submitted to initiate KYC |
| [retrieveCustomerId](retrieve-customer-id.md) | [kotlin]<br>open suspend override fun [retrieveCustomerId](retrieve-customer-id.md)(): String<br>Fetches the customer's unique identifier, prioritizing a cached version for efficiency. If the ID is not available in the cache, it initiates a server request to obtain it. |
| [retrieveKycId](retrieve-kyc-id.md) | [kotlin]<br>open suspend override fun [retrieveKycId](retrieve-kyc-id.md)(): String<br>Retrieve KYC Id |
| [uploadKyc](upload-kyc.md) | [kotlin]<br>open suspend override fun [uploadKyc](upload-kyc.md)(body: String, documents: Map&lt;String, File&gt;): [CreateKycResponse](../../com.trustless.requests.kyc.createKyc/-create-kyc-response/index.md)<br>Uploads KYC documents |
