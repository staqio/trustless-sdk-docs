//[trustless](../../../index.md)/[com.trustless.paginator](../index.md)/[Paginator](index.md)

# Paginator

[kotlin]\
class [Paginator](index.md)&lt;[T](index.md)&gt;

Facilitates pagination by encapsulating the logic required to manage paginated requests. This class unifies the process of fetching paginated data from a server, tracking current page and page size, and executing requests for data as needed.

## Types

| Name | Summary |
|---|---|
| [Builder](-builder/index.md) | [kotlin]<br>class [Builder](-builder/index.md)&lt;[T](-builder/index.md)&gt;(request: [PaginationRequest](../-pagination-request/index.md)&lt;[List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[T](-builder/index.md)&gt;&gt;, args: [UrlQueryParams](../../com.trustless.queryParams/-url-query-params/index.md)) |

## Functions

| Name | Summary |
|---|---|
| [fetchFirst](fetch-first.md) | [kotlin]<br>suspend fun [fetchFirst](fetch-first.md)(): [PaginatedResponse](../-paginated-response/index.md)&lt;[List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[T](index.md)&gt;&gt;<br>Fetches the first page of results and resets the internal page counter to 1, ensuring the pagination starts from the beginning. |
| [fetchNext](fetch-next.md) | [kotlin]<br>suspend fun [fetchNext](fetch-next.md)(): [PaginatedResponse](../-paginated-response/index.md)&lt;[List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[T](index.md)&gt;&gt;<br>Retrieves the next page of results, automatically increments the internal page counter, and returns a paginated response. |
| [isFetching](is-fetching.md) | [kotlin]<br>fun [isFetching](is-fetching.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if data is currently being fetched. |
| [isLastPage](is-last-page.md) | [kotlin]<br>fun [isLastPage](is-last-page.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Determines if the last page of results has been reached based on the internal page counter and the total number of pages available. |
