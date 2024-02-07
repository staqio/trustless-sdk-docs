//[trustless](../../../index.md)/[com.trustless.paginator](../index.md)/[Paginator](index.md)

# Paginator

[kotlin]\
class [Paginator](index.md)&lt;[T](index.md)&gt;

## Types

| Name | Summary |
|---|---|
| [Builder](-builder/index.md) | [kotlin]<br>class [Builder](-builder/index.md)&lt;[T](-builder/index.md)&gt;(request: [PaginationRequest](../-pagination-request/index.md)&lt;[List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[T](-builder/index.md)&gt;&gt;, args: [UrlQueryParams](../../com.trustless.queryParams/-url-query-params/index.md)) |

## Functions

| Name | Summary |
|---|---|
| [fetchFirst](fetch-first.md) | [kotlin]<br>suspend fun [fetchFirst](fetch-first.md)(): [PaginatedResponse](../-paginated-response/index.md)&lt;[List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[T](index.md)&gt;&gt; |
| [fetchNext](fetch-next.md) | [kotlin]<br>suspend fun [fetchNext](fetch-next.md)(): [PaginatedResponse](../-paginated-response/index.md)&lt;[List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[T](index.md)&gt;&gt; |
| [isFetching](is-fetching.md) | [kotlin]<br>fun [isFetching](is-fetching.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isLastPage](is-last-page.md) | [kotlin]<br>fun [isLastPage](is-last-page.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
