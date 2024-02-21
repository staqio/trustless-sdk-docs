//[trustless](../../../index.md)/[com.trustless](../index.md)/[TrustlessSDK](index.md)/[securityProviderFailed](security-provider-failed.md)

# securityProviderFailed

[kotlin]\
suspend fun [securityProviderFailed](security-provider-failed.md)()

Notifies the system that an attempt to update the security provider has failed. This suspend function should be called when the application is unable to update the security provider, indicating a failure in the update process. It communicates this failure to the TrustlessSDK or relevant system component, triggering any necessary fallback or error handling procedures.

#### Throws

| | |
|---|---|
| [TrustlessNotInitializedSdkException](../../com.trustless.exceptions/-trustless-not-initialized-sdk-exception/index.md) | Is thrown when trying to access this method while sdk is not initialized |
