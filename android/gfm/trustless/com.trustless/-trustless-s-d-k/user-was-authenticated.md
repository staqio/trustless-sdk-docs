//[trustless](../../../index.md)/[com.trustless](../index.md)/[TrustlessSDK](index.md)/[userWasAuthenticated](user-was-authenticated.md)

# userWasAuthenticated

[kotlin]\
suspend fun [userWasAuthenticated](user-was-authenticated.md)()

Notifies the SDK that the user has successfully authenticated. This function should be called after a user completes the authentication process. Invoking this method can trigger internal SDK processes that depend on user authentication status, such as enabling certain features or accessing authenticated user data.
