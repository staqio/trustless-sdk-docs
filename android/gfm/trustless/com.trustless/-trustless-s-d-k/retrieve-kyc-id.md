//[trustless](../../../index.md)/[com.trustless](../index.md)/[TrustlessSDK](index.md)/[retrieveKycId](retrieve-kyc-id.md)

# retrieveKycId

[kotlin]\
suspend fun [retrieveKycId](retrieve-kyc-id.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)

Retrieve KYC Id

[Server Api Reference](https://developer.staq.io/docs/apis/kyc#/Customers/Get%20KYC%20Id)

Fetches the kyc id, prioritizing a cached version for efficiency. If the ID is not available in the cache, it initiates a server request to obtain it.

#### Return

Kyc id

#### Throws

| | |
|---|---|
| [TrustlessException](../../com.trustless.exceptions/-trustless-exception/index.md) | Is thrown when the server returns custom error, or when error was not expected by the SDK |
| [TrustlessUserTokenExpiredException](../../com.trustless.exceptions/-trustless-user-token-expired-exception/index.md) | Is thrown when the token expires, either due to time period or server forced expiration |
| [TrustlessMalformedResponse](../../com.trustless.exceptions/-trustless-malformed-response/index.md) | Is thrown when server returned unexpected format of the data |
| CancellationException | Is thrown usually when the developer cancels the coroutine |
