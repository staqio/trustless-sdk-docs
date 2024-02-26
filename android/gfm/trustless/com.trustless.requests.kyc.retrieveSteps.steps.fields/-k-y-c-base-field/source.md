//[trustless](../../../index.md)/[com.trustless.requests.kyc.retrieveSteps.steps.fields](../index.md)/[KYCBaseField](index.md)/[source](source.md)

# source

[kotlin]\
open override val [source](source.md): [KYCInputType](../../com.trustless.requests.kyc.retrieveSteps/-k-y-c-input-type/index.md)

the source of data for the field, could be: USER, INPUT, UNKNOWN, SDK, DOCUMENT

where UNKNOWN is returned when server returned a new type that the SDK is not handling. Prompt the user to update the app
