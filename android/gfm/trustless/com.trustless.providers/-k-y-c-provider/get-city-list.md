//[trustless](../../../index.md)/[com.trustless.providers](../index.md)/[KYCProvider](index.md)/[getCityList](get-city-list.md)

# getCityList

[kotlin]\
abstract suspend fun [getCityList](get-city-list.md)(countryCode: String): [RetrieveQuestionsResponse](../../com.trustless.requests.kyc.retrieveQuestions/-retrieve-questions-response/index.md)

Retrieves list of values defined by URI parameter {listname} and optionally filtered by the value of the query parameter {filtervalue}

#### Parameters

kotlin

| | |
|---|---|
| countryCode | Country code that you get from CountryCode field while KYC process. You can use [com.trustless.requests.kyc.retrieveSteps.steps.fields.KYCUrlField.getValueFromDependentField](../../com.trustless.requests.kyc.retrieveSteps.steps.fields/-k-y-c-url-field/get-value-from-dependent-field.md) from [com.trustless.requests.kyc.retrieveSteps.steps.fields.KYCUrlField](../../com.trustless.requests.kyc.retrieveSteps.steps.fields/-k-y-c-url-field/index.md) class. |

#### Throws

| | |
|---|---|
| [TrustlessException](../../com.trustless.exceptions/-trustless-exception/index.md) | Is thrown when the server returns custom error, or when error was not expected by the SDK |
| [TrustlessAppTokenException](../../com.trustless.exceptions/-trustless-app-token-exception/index.md) | Is thrown when the token expires, either due to time period or server forced expiration |
| [TrustlessMalformedResponse](../../com.trustless.exceptions/-trustless-malformed-response/index.md) | Is thrown when server returned unexpected format of the data |
| [TrustlessExceptionListener](../../com.trustless.exceptions/-trustless-exception-listener/index.md) | Is thrown when developer has not set security listener |
| [TrustlessExceptionSecurityProviderIsNotInstalled](../../com.trustless.exceptions/-trustless-exception-security-provider-is-not-installed/index.md) | Is thrown when user's device doesn't have a security provider |
| CancellationException | Is thrown usually when the developer cancels the coroutine |
| [TrustlessNotInitializedSdkException](../../com.trustless.exceptions/-trustless-not-initialized-sdk-exception/index.md) | Is thrown when trying to access this method while sdk is not initialized |
