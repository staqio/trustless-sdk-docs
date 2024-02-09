//[trustless](../../../index.md)/[com.trustless.paginator](../index.md)/[Paginator](index.md)/[fetchNext](fetch-next.md)

# fetchNext

[kotlin]\
suspend fun [fetchNext](fetch-next.md)(): [PaginatedResponse](../-paginated-response/index.md)&lt;[List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[T](index.md)&gt;&gt;

Retrieves the next page of results, automatically increments the internal page counter, and returns a paginated response.

#### Return

PaginatedResponse<List<T>> containing the data for the next page.
