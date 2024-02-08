//[trustless](../../../index.md)/[com.trustless](../index.md)/[TrustlessSDK](index.md)/[setLogoutListener](set-logout-listener.md)

# setLogoutListener

[kotlin]\
fun [setLogoutListener](set-logout-listener.md)(cb: () -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html))

Registers a callback function to be invoked upon the expiration of a user's authentication token or when the `logout` method is explicitly called. This listener provides a mechanism for performing cleanup, updating UI, or triggering other necessary actions immediately after a user logs out or their session ends.

Usage example: setLogoutListener {     // Code to execute on logout }

#### Parameters

kotlin

| | |
|---|---|
| cb | The callback function to be executed when the user's token expires or the logout method is invoked. |
