//[trustless](../../../index.md)/[com.trustless.paginator](../index.md)/[PaginatorWithPageNumber](index.md)

# PaginatorWithPageNumber

[kotlin]\
class [PaginatorWithPageNumber](index.md)&lt;[T](index.md)&gt; : [Paginator](../-paginator/index.md)&lt;[T](index.md)&gt;

## Functions

| Name | Summary |
|---|---|
| [fetchFirst](fetch-first.md) | [kotlin]<br>open suspend override fun [fetchFirst](fetch-first.md)(): [PaginatedResponse](../-paginated-response/index.md)&lt;List&lt;[T](index.md)&gt;&gt;<br>Fetches the first page of results and resets the internal page counter to 1, ensuring the pagination starts from the beginning. |
| [fetchNext](fetch-next.md) | [kotlin]<br>open suspend override fun [fetchNext](fetch-next.md)(): [PaginatedResponse](../-paginated-response/index.md)&lt;List&lt;[T](index.md)&gt;&gt;<br>Retrieves the next page of results, automatically increments the internal page counter, and returns a paginated response. |
| [isFetching](is-fetching.md) | [kotlin]<br>open override fun [isFetching](is-fetching.md)(): Boolean<br>Checks if data is currently being fetched. |
| [isLastPage](is-last-page.md) | [kotlin]<br>open override fun [isLastPage](is-last-page.md)(): Boolean<br>Determines if the last page of results has been reached based on the internal page counter and the total number of pages available. |
