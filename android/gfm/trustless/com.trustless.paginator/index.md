//[trustless](../../index.md)/[com.trustless.paginator](index.md)

# Package-level declarations

## Types

| Name | Summary |
|---|---|
| [PaginatedResponse](-paginated-response/index.md) | [kotlin]<br>data class [PaginatedResponse](-paginated-response/index.md)&lt;[T](-paginated-response/index.md)&gt;<br>Represents a paginated response from the server, encapsulating the returned data along with pagination details. |
| [Paginator](-paginator/index.md) | [kotlin]<br>interface [Paginator](-paginator/index.md)&lt;[T](-paginator/index.md)&gt;<br>Facilitates pagination by encapsulating the logic required to manage paginated requests. This class unifies the process of fetching paginated data from a server, tracking current page and page size, and executing requests for data as needed. |
| [PaginatorWithPageNumber](-paginator-with-page-number/index.md) | [kotlin]<br>class [PaginatorWithPageNumber](-paginator-with-page-number/index.md)&lt;[T](-paginator-with-page-number/index.md)&gt; : [Paginator](-paginator/index.md)&lt;[T](-paginator-with-page-number/index.md)&gt; |
