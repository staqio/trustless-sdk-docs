//[trustless](../../../index.md)/[com.trustless](../index.md)/[TrustlessSDK](index.md)/[getSteps](get-steps.md)

# getSteps

[kotlin]\
suspend fun [getSteps](get-steps.md)(sourceFields: [SourceFieldsMap](../../com.trustless.requests.kyc.retrieveSteps.steps/-source-fields-map/index.md)): [AllKYCSteps](../../com.trustless.requests.kyc.retrieveSteps.steps/-all-k-y-c-steps/index.md)

Retrieves JSON descriptor of the data that should be collected by partner application and submitted to initiate KYC

[Server Api Reference](https://developer.staq.io/docs/apis/kyc#/Metadata/Get%20KYC%20attributes)

For more information refer to KYC section in the documentation

#### Parameters

kotlin

| | |
|---|---|
| sourceFields | is a map in the following format json.put(&quot;fullNameNationalLanguage&quot;, fullNameNationalLanguageValue.visualZone); let json = SourceFieldsMap() json.put(&quot;optionalDataFirstLine&quot;, &quot;String&quot;) json.put(&quot;nationality&quot;, &quot;String&quot;) json.put(&quot;fullName&quot;, &quot;String&quot;) json.put(&quot;documentNumber&quot;, &quot;String&quot;) json.put(&quot;dateOfExpiry&quot;, &quot;String&quot;) json.put(&quot;frontCard&quot;, File) json.put(&quot;backCard&quot;, File) json.put(&quot;dateOfBirth&quot;, &quot;String&quot;) json.put(&quot;gender&quot;, &quot;String&quot;) json.put(&quot;selfieImage&quot;, File) json.put(&quot;selfieVideo&quot;, File) |

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
