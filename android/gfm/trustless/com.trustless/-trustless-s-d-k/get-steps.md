//[trustless](../../../index.md)/[com.trustless](../index.md)/[TrustlessSDK](index.md)/[getSteps](get-steps.md)

# getSteps

[kotlin]\
suspend fun [getSteps](get-steps.md)(sourceFields: [SourceFieldsMap](../../com.trustless.requests.kyc.retrieveSteps.steps/-source-fields-map/index.md)): [AllKYCSteps](../../com.trustless.requests.kyc.retrieveSteps.steps/-all-k-y-c-steps/index.md)

[Api Reference](https://developer.staq.io/docs/apis/kyc#/Metadata/Get%20KYC%20attributes) For more information refer to KYC section in the documentation

#### Parameters

kotlin

| | |
|---|---|
| sourceFields | is a map in the following format json.put(&quot;fullNameNationalLanguage&quot;, fullNameNationalLanguageValue.visualZone); let json = SourceFieldsMap() json.put(&quot;optionalDataFirstLine&quot;, &quot;String&quot;) json.put(&quot;nationality&quot;, &quot;String&quot;) json.put(&quot;fullName&quot;, &quot;String&quot;) json.put(&quot;documentNumber&quot;, &quot;String&quot;) json.put(&quot;dateOfExpiry&quot;, &quot;String&quot;) json.put(&quot;frontCard&quot;, File) json.put(&quot;backCard&quot;, File) json.put(&quot;dateOfBirth&quot;, &quot;String&quot;) json.put(&quot;gender&quot;, &quot;String&quot;) json.put(&quot;selfieImage&quot;, File) json.put(&quot;selfieVideo&quot;, File) |
