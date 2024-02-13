//[trustless](../../../index.md)/[com.trustless](../index.md)/[TrustlessSDK](index.md)/[getPurposes](get-purposes.md)

# getPurposes

[kotlin]\
suspend fun [getPurposes](get-purposes.md)(params: [GetPurposesRequestParams](../../com.trustless.requests.cliq/-get-purposes-request-params/index.md)): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[StaqPurpose](../../com.trustless.requests.cliq/-staq-purpose/index.md)&gt;

Returns all purpose codes related to cliq customer

[Server Api Reference](https://developer.staq.io/docs/apis/cliq#/Aliases/List%20all%20purpose%20codes)

#### Parameters

kotlin

| | |
|---|---|
| params | Get purposes params |

#### Throws

| | |
|---|---|
| [TrustlessException](../../com.trustless.exceptions/-trustless-exception/index.md) | Is thrown when the server returns custom error, or when error was not expected by the SDK |
| [TrustlessUserTokenExpiredException](../../com.trustless.exceptions/-trustless-user-token-expired-exception/index.md) | Is thrown when the token expires, either due to time period or server forced expiration |
| [TrustlessMalformedResponse](../../com.trustless.exceptions/-trustless-malformed-response/index.md) | Is thrown when server returned unexpected format of the data |
| CancellationException | Is thrown usually when the developer cancels the coroutine |
