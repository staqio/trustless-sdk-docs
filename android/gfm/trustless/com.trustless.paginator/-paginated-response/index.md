//[trustless](../../../index.md)/[com.trustless.paginator](../index.md)/[PaginatedResponse](index.md)

# PaginatedResponse

data class [PaginatedResponse](index.md)&lt;[T](index.md)&gt;

Represents a paginated response from the server, encapsulating the returned data along with pagination details.

#### Parameters

kotlin

| | |
|---|---|
| T | The type of data contained in the response. |
| data | The data returned from the server for the current page. |
| totalPages | The total number of pages available. |
| pageSize | The number of items per page. |
| currentPage | The index of the current page, starting from 1. |

## Properties

| Name | Summary |
|---|---|
| [currentPage](current-page.md) | [kotlin]<br>val [currentPage](current-page.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [data](data.md) | [kotlin]<br>val [data](data.md): [T](index.md) |
| [pageSize](page-size.md) | [kotlin]<br>val [pageSize](page-size.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [totalPages](total-pages.md) | [kotlin]<br>val [totalPages](total-pages.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |