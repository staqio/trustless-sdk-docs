//[trustless](../../../index.md)/[com.trustless](../index.md)/[TrustlessSDK](index.md)/[retrieveCustomerId](retrieve-customer-id.md)

# retrieveCustomerId

[kotlin]\
suspend fun [retrieveCustomerId](retrieve-customer-id.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)

[Server Api Reference](https://developer.finto.io/docs/apis/kyc#/Customers/Get%20Customer%20Status)

Fetches the customer's unique identifier, prioritizing a cached version for efficiency. If the ID is not available in the cache, it initiates a server request to obtain it.

#### Return

Customer id

#### Throws

| | |
|---|---|
| [TrustlessException](../../com.trustless.exceptions/-trustless-exception/index.md) | Is thrown when the server returns custom error, or when error was not expected by the SDK |
| [TrustlessUserTokenExpiredException](../../com.trustless.exceptions/-trustless-user-token-expired-exception/index.md) | Is thrown when the token expires, either due to time period or server forced expiration |
| [TrustlessMalformedResponse](../../com.trustless.exceptions/-trustless-malformed-response/index.md) | Is thrown when server returned unexpected format of the data |
| CancellationException | Is thrown usually when the developer cancels the coroutine |
