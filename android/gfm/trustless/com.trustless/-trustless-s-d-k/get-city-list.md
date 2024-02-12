//[trustless](../../../index.md)/[com.trustless](../index.md)/[TrustlessSDK](index.md)/[getCityList](get-city-list.md)

# getCityList

[kotlin]\
suspend fun [getCityList](get-city-list.md)(countryCode: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [RetrieveQuestionsResponse](../../com.trustless.requests.kyc.retrieveQuestions/-retrieve-questions-response/index.md)

Retrieves list of values defined by URI parameter {listname} and optionally filtered by the value of the query parameter {filtervalue}

[Server Api Reference](https://developer.staq.io/docs/apis/kyc#/Metadata/Get%20a%20List%20of%20Values)

#### Parameters

kotlin

| | |
|---|---|
| countryCode | Country code that you get from CountryCode field while KYC process. You can use [com.trustless.requests.kyc.retrieveSteps.steps.fields.UrlField.getValueFromDependentField](../../com.trustless.requests.kyc.retrieveSteps.steps.fields/-url-field/get-value-from-dependent-field.md) from [com.trustless.requests.kyc.retrieveSteps.steps.fields.UrlField](../../com.trustless.requests.kyc.retrieveSteps.steps.fields/-url-field/index.md) class. |