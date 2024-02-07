//[trustless](../../../index.md)/[com.trustless.serializers](../index.md)/[PaginationSerializer](index.md)

# PaginationSerializer

[]\
class [PaginationSerializer](index.md)&lt;[T](index.md)&gt;(serializer: KSerializer&lt;[T](index.md)&gt;) : [ResponseSerializer](../-response-serializer/index.md)&lt;[PaginatedResponse](../../com.trustless.paginator/-paginated-response/index.md)&lt;[List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[T](index.md)&gt;&gt;&gt;

## Constructors

| | |
|---|---|
| [PaginationSerializer](-pagination-serializer.md) | []<br>constructor(serializer: KSerializer&lt;[T](index.md)&gt;) |

## Functions

| Name | Summary |
|---|---|
| [serialize](serialize.md) | []<br>open override fun [serialize](serialize.md)(response: Response): [PaginatedResponse](../../com.trustless.paginator/-paginated-response/index.md)&lt;[List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[T](index.md)&gt;&gt; |
