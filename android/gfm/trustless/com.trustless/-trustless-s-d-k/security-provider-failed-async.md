//[trustless](../../../index.md)/[com.trustless](../index.md)/[TrustlessSDK](index.md)/[securityProviderFailedAsync](security-provider-failed-async.md)

# securityProviderFailedAsync

[kotlin]\
fun [securityProviderFailedAsync](security-provider-failed-async.md)(callback: [AsyncCallback](../../com.trustless.utils/-async-callback/index.md)&lt;Unit&gt;? = null)

Asynchronously notifies the system of a failure to update the security provider. This function wraps the securityProviderFailed suspend function, allowing it to be called from non-suspend contexts and providing an optional callback for handling completion.

#### Parameters

kotlin

| | |
|---|---|
| callback | An optional callback of type AsyncCallback<Unit> that is invoked upon completion. |
