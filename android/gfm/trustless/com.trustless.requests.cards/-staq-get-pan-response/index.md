//[trustless](../../../index.md)/[com.trustless.requests.cards](../index.md)/[StaqGetPanResponse](index.md)

# StaqGetPanResponse

@Serializable

data class [StaqGetPanResponse](index.md)(val token: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val pan: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))

Get Pan Response

#### Parameters

kotlin

| | |
|---|---|
| token | The unique card identifier (non-sensitive information) |
| pan | Full unmasked card number (sensitive information) |

## Constructors

| | |
|---|---|
| [StaqGetPanResponse](-staq-get-pan-response.md) | [kotlin]<br>constructor(token: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), pan: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |

## Properties

| Name | Summary |
|---|---|
| [pan](pan.md) | [kotlin]<br>@SerialName(value = &quot;PAN&quot;)<br>val [pan](pan.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [token](token.md) | [kotlin]<br>@SerialName(value = &quot;Token&quot;)<br>val [token](token.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
