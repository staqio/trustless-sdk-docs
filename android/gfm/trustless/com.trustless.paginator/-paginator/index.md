//[trustless](../../../index.md)/[com.trustless.paginator](../index.md)/[Paginator](index.md)

# Paginator

interface [Paginator](index.md)&lt;[T](index.md)&gt;

Facilitates pagination by encapsulating the logic required to manage paginated requests. This class unifies the process of fetching paginated data from a server, tracking current page and page size, and executing requests for data as needed.

#### Inheritors

| |
|---|
| [PaginatorWithPageNumber](../-paginator-with-page-number/index.md) |

## Functions

| Name | Summary |
|---|---|
| [fetchFirst](fetch-first.md) | [kotlin]<br>abstract suspend fun [fetchFirst](fetch-first.md)(): [PaginatedResponse](../-paginated-response/index.md)&lt;List&lt;[T](index.md)&gt;&gt;<br>Fetches the first page of results and resets the internal page counter to 1, ensuring the pagination starts from the beginning. |
| [fetchNext](fetch-next.md) | [kotlin]<br>abstract suspend fun [fetchNext](fetch-next.md)(): [PaginatedResponse](../-paginated-response/index.md)&lt;List&lt;[T](index.md)&gt;&gt;<br>Retrieves the next page of results, automatically increments the internal page counter, and returns a paginated response. |
| [isFetching](is-fetching.md) | [kotlin]<br>abstract fun [isFetching](is-fetching.md)(): Boolean<br>Checks if data is currently being fetched. |
| [isLastPage](is-last-page.md) | [kotlin]<br>abstract fun [isLastPage](is-last-page.md)(): Boolean<br>Determines if the last page of results has been reached based on the internal page counter and the total number of pages available. |
