//[trustless](../../../index.md)/[com.trustless](../index.md)/[TrustlessSDK](index.md)/[logout](logout.md)

# logout

[kotlin]\
suspend fun [logout](logout.md)()

This endpoint is used to invalidate the token, and to remove the data of the current user from the memory. Refer to the Advanced section about deinitialization for more details

[Server Api Reference](https://developer.staq.io/docs/apis/identity#/Authentication/Logout%20User)

#### Throws

| | |
|---|---|
| [TrustlessException](../../com.trustless.exceptions/-trustless-exception/index.md) | Is thrown when the server returns custom error, or when error was not expected by the SDK |
| [TrustlessUserTokenExpiredException](../../com.trustless.exceptions/-trustless-user-token-expired-exception/index.md) | Is thrown when the token expires, either due to time period or server forced expiration |
| [TrustlessMalformedResponse](../../com.trustless.exceptions/-trustless-malformed-response/index.md) | Is thrown when server returned unexpected format of the data |
| CancellationException | Is thrown usually when the developer cancels the coroutine |
