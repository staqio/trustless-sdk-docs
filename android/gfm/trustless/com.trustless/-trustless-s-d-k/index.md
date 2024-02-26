//[trustless](../../../index.md)/[com.trustless](../index.md)/[TrustlessSDK](index.md)

# TrustlessSDK

[kotlin]\
class [TrustlessSDK](index.md)

## Types

| Name | Summary |
|---|---|
| [Companion](-companion/index.md) | [kotlin]<br>object [Companion](-companion/index.md) |

## Functions

| Name | Summary |
|---|---|
| [clearLogoutListener](clear-logout-listener.md) | [kotlin]<br>fun [clearLogoutListener](clear-logout-listener.md)()<br>Removes the previously set logout listener. This function must be called after user's logout. |
| [isAbleToLogInUsingBiometry](is-able-to-log-in-using-biometry.md) | [kotlin]<br>fun [isAbleToLogInUsingBiometry](is-able-to-log-in-using-biometry.md)(): Boolean<br>Determines whether the user has the option to authenticate using biometric credentials. |
| [securityProviderFailed](security-provider-failed.md) | [kotlin]<br>suspend fun [securityProviderFailed](security-provider-failed.md)()<br>Notifies the system that an attempt to update the security provider has failed. This suspend function should be called when the application is unable to update the security provider, indicating a failure in the update process. It communicates this failure to the TrustlessSDK or relevant system component, triggering any necessary fallback or error handling procedures. |
| [securityProviderFailedAsync](security-provider-failed-async.md) | [kotlin]<br>fun [securityProviderFailedAsync](security-provider-failed-async.md)(callback: [AsyncCallback](../../com.trustless.utils/-async-callback/index.md)&lt;Unit&gt;? = null)<br>Asynchronously notifies the system of a failure to update the security provider. This function wraps the securityProviderFailed suspend function, allowing it to be called from non-suspend contexts and providing an optional callback for handling completion. |
| [securityProviderSuccess](security-provider-success.md) | [kotlin]<br>suspend fun [securityProviderSuccess](security-provider-success.md)()<br>Notifies the system that the security provider has been successfully updated. This suspend function should be called following a successful update of the security provider, signaling a successful outcome in the update process. It communicates this success to the TrustlessSDK or relevant system component to continue normal operation. |
| [securityProviderSuccessAsync](security-provider-success-async.md) | [kotlin]<br>fun [securityProviderSuccessAsync](security-provider-success-async.md)(callback: [AsyncCallback](../../com.trustless.utils/-async-callback/index.md)&lt;Unit&gt;? = null)<br>Asynchronously notifies the system of the successful update of the security provider. Similar to securityProviderFailedAsync, this function provides an asynchronous wrapper for securityProviderSuccess, facilitating its invocation from non-suspend contexts with an optional callback for handling completion. |
| [setLogoutListener](set-logout-listener.md) | [kotlin]<br>fun [setLogoutListener](set-logout-listener.md)(cb: () -&gt; Unit)<br>Registers a callback function to be invoked upon the expiration of a user's authentication token or when the `logout` method is explicitly called. This listener provides a mechanism for performing cleanup, updating UI, or triggering other necessary actions immediately after a user logs out or their session ends. |
| [subscribeToBiometryRequest](subscribe-to-biometry-request.md) | [kotlin]<br>fun [subscribeToBiometryRequest](subscribe-to-biometry-request.md)(listener: () -&gt; Unit)<br>Registers a callback to be invoked when biometric authentication is required. This function allows the application to respond to SDK requests for biometric authentication, typically by prompting the user to authenticate using their biometric credentials (e.g., fingerprint, facial recognition). |
| [subscribeToSecurityProviderUpdate](subscribe-to-security-provider-update.md) | [kotlin]<br>fun [subscribeToSecurityProviderUpdate](subscribe-to-security-provider-update.md)(listener: (Int, Intent?) -&gt; Unit)<br>Subscribes to updates regarding the need to refresh or update the security provider within the application. This method sets a listener that gets triggered with an error code and an optional Intent when the application detects that the security provider needs to be updated. This is typically used in conjunction with GoogleApiAvailability to handle scenarios where the security provider can be updated by the user to ensure the application's security integrity. |
| [userWasAuthenticated](user-was-authenticated.md) | [kotlin]<br>suspend fun [userWasAuthenticated](user-was-authenticated.md)()<br>Notifies the SDK that the user has successfully authenticated. This function should be called after a user completes the authentication process. Invoking this method can trigger internal SDK processes that depend on user authentication status, such as enabling certain features or accessing authenticated user data. |
