//[trustless](../../../index.md)/[com.trustless.requests.cards](../index.md)/[StaqGetCVVResponse](index.md)

# StaqGetCVVResponse

@Serializable

data class [StaqGetCVVResponse](index.md)(val token: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val pan: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val cvv: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))

Get Pan with CVV Response

#### Parameters

kotlin

| | |
|---|---|
| token | The unique card identifier (non-sensitive information) |
| pan | Full unmasked card number (sensitive information) |
| cvv | CVV code required for the card authorization (sensitive information) MAXLENGTH: 3 MINLENGTH: 3 |

## Constructors

| | |
|---|---|
| [StaqGetCVVResponse](-staq-get-c-v-v-response.md) | [kotlin]<br>constructor(token: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), pan: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), cvv: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |

## Properties

| Name | Summary |
|---|---|
| [cvv](cvv.md) | [kotlin]<br>@SerialName(value = &quot;CVV&quot;)<br>val [cvv](cvv.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [pan](pan.md) | [kotlin]<br>@SerialName(value = &quot;PAN&quot;)<br>val [pan](pan.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [token](token.md) | [kotlin]<br>@SerialName(value = &quot;Token&quot;)<br>val [token](token.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
