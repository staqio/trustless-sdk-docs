//[trustless](../../../index.md)/[com.trustless](../index.md)/[TrustlessSDK](index.md)/[securityProviderSuccessAsync](security-provider-success-async.md)

# securityProviderSuccessAsync

[kotlin]\
fun [securityProviderSuccessAsync](security-provider-success-async.md)(callback: [AsyncCallback](../../com.trustless.utils/-async-callback/index.md)&lt;Unit&gt;? = null)

Asynchronously notifies the system of the successful update of the security provider. Similar to securityProviderFailedAsync, this function provides an asynchronous wrapper for securityProviderSuccess, facilitating its invocation from non-suspend contexts with an optional callback for handling completion.

#### Parameters

kotlin

| | |
|---|---|
| callback | An optional callback of type AsyncCallback<Unit> that is invoked upon completion. |
