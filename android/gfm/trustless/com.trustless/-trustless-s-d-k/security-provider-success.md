//[trustless](../../../index.md)/[com.trustless](../index.md)/[TrustlessSDK](index.md)/[securityProviderSuccess](security-provider-success.md)

# securityProviderSuccess

[kotlin]\
suspend fun [securityProviderSuccess](security-provider-success.md)()

Notifies the system that the security provider has been successfully updated. This suspend function should be called following a successful update of the security provider, signaling a successful outcome in the update process. It communicates this success to the TrustlessSDK or relevant system component to continue normal operation.

#### Throws

| | |
|---|---|
| [TrustlessNotInitializedSdkException](../../com.trustless.exceptions/-trustless-not-initialized-sdk-exception/index.md) | Is thrown when trying to access this method while sdk is not initialized |
