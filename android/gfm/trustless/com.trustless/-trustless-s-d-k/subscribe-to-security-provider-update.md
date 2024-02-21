//[trustless](../../../index.md)/[com.trustless](../index.md)/[TrustlessSDK](index.md)/[subscribeToSecurityProviderUpdate](subscribe-to-security-provider-update.md)

# subscribeToSecurityProviderUpdate

[kotlin]\
fun [subscribeToSecurityProviderUpdate](subscribe-to-security-provider-update.md)(listener: (Int, Intent?) -&gt; Unit)

Subscribes to updates regarding the need to refresh or update the security provider within the application. This method sets a listener that gets triggered with an error code and an optional Intent when the application detects that the security provider needs to be updated. This is typically used in conjunction with GoogleApiAvailability to handle scenarios where the security provider can be updated by the user to ensure the application's security integrity.

GoogleApiAvailability.getInstance().apply {     if (isUserResolvableError(errorCode)) {        showErrorDialogFragment(this@MainActivity, errorCode, SECURITY_PROVIDER_CODE) {            TrustlessSDK.instance.securityProviderFailedAsync()        }     } else {        TrustlessSDK.instance.securityProviderFailedAsync()     } }

#### Parameters

kotlin

| | |
|---|---|
| listener | A lambda function that takes an error code (Int) and an optional Intent (Intent?) as parameters. |

#### Throws

| | |
|---|---|
| [TrustlessNotInitializedSdkException](../../com.trustless.exceptions/-trustless-not-initialized-sdk-exception/index.md) | Is thrown when trying to access this method while sdk is not initialized |
