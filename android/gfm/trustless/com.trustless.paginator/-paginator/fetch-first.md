//[trustless](../../../index.md)/[com.trustless.paginator](../index.md)/[Paginator](index.md)/[fetchFirst](fetch-first.md)

# fetchFirst

[kotlin]\
suspend fun [fetchFirst](fetch-first.md)(): [PaginatedResponse](../-paginated-response/index.md)&lt;[List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[T](index.md)&gt;&gt;

Fetches the first page of results and resets the internal page counter to 1, ensuring the pagination starts from the beginning.

#### Return

PaginatedResponse<List<T>> containing the data for the first page.
