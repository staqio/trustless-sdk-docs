//[trustless](../../../index.md)/[com.trustless](../index.md)/[TrustlessSDK](index.md)/[retrieveUser](retrieve-user.md)

# retrieveUser

[kotlin]\
suspend fun [retrieveUser](retrieve-user.md)(): [StaqRetrieveUserResponse](../../com.trustless.requests.identity/-staq-retrieve-user-response/index.md)

Retrieves the details of an existing user

[Server Api Reference](https://developer.staq.io/docs/apis/identity#/User%20management/Retrieve%20a%20user)

#### Throws

| | |
|---|---|
| [TrustlessException](../../com.trustless.exceptions/-trustless-exception/index.md) | Is thrown when the server returns custom error, or when error was not expected by the SDK |
| [TrustlessUserTokenExpiredException](../../com.trustless.exceptions/-trustless-user-token-expired-exception/index.md) | Is thrown when the token expires, either due to time period or server forced expiration |
| [TrustlessMalformedResponse](../../com.trustless.exceptions/-trustless-malformed-response/index.md) | Is thrown when server returned unexpected format of the data |
| CancellationException | Is thrown usually when the developer cancels the coroutine |
