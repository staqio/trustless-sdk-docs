//[trustless](../../../index.md)/[com.trustless.paginator](../index.md)/[Paginator](index.md)/[fetchNext](fetch-next.md)

# fetchNext

[kotlin]\
suspend fun [fetchNext](fetch-next.md)(): [PaginatedResponse](../-paginated-response/index.md)&lt;[List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[T](index.md)&gt;&gt;

Retrieves the next page of results, automatically increments the internal page counter, and returns a paginated response.

#### Return

PaginatedResponse<List<T>> containing the data for the next page.

#### Throws

| | |
|---|---|
| [TrustlessException](../../com.trustless.exceptions/-trustless-exception/index.md) | Is thrown when the server returns custom error, or when error was not expected by the SDK |
| [TrustlessUserTokenExpiredException](../../com.trustless.exceptions/-trustless-user-token-expired-exception/index.md) | Is thrown when the token expires, either due to time period or server forced expiration |
| [TrustlessMalformedResponse](../../com.trustless.exceptions/-trustless-malformed-response/index.md) | Is thrown when server returned unexpected format of the data |
| CancellationException | Is thrown usually when the developer cancels the coroutine |
