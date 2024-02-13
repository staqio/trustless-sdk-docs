//[trustless](../../../index.md)/[com.trustless](../index.md)/[TrustlessSDK](index.md)/[login](login.md)

# login

[kotlin]\
suspend fun [login](login.md)(params: [UserTokenRequestParams](../../com.trustless.requests.identity.userToken/-user-token-request-params/index.md), useBiometry: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [StaqUserTokenResponse](../../com.trustless.requests.identity/-staq-user-token-response/index.md)

Returns access token for an application or user

[Server Api Reference](https://developer.staq.io/docs/apis/identity#/Authentication/Get%20access%20token)

#### Parameters

kotlin

| | |
|---|---|
| useBiometry | if true every 5 minutes you would need to authenticate with biometry/password/etc refer to the Using biometry section in the main documentation. |
| params | params to log in |

#### Throws

| | |
|---|---|
| [TrustlessException](../../com.trustless.exceptions/-trustless-exception/index.md) | Is thrown when the server returns custom error, or when error was not expected by the SDK |
| [TrustlessUserTokenExpiredException](../../com.trustless.exceptions/-trustless-user-token-expired-exception/index.md) | Is thrown when the token expires, either due to time period or server forced expiration |
| [TrustlessMalformedResponse](../../com.trustless.exceptions/-trustless-malformed-response/index.md) | Is thrown when server returned unexpected format of the data |
| CancellationException | Is thrown usually when the developer cancels the coroutine |
