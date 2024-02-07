//[trustless](../../../index.md)/[com.trustless.requests.cards](../index.md)/[StaqSetLimitResponse](index.md)

# StaqSetLimitResponse

[]\
@Serializable

data class [StaqSetLimitResponse](index.md)(val periodRaw: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val typeRaw: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val limit: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), val status: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))

## Constructors

| | |
|---|---|
| [StaqSetLimitResponse](-staq-set-limit-response.md) | []<br>constructor(periodRaw: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), typeRaw: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), limit: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), status: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |

## Properties

| Name | Summary |
|---|---|
| [limit](limit.md) | []<br>@SerialName(value = &quot;Limit&quot;)<br>val [limit](limit.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [period](period.md) | []<br>val [period](period.md): [StaqCardLimitPeriod](../-staq-card-limit-period/index.md)? |
| [periodRaw](period-raw.md) | []<br>@SerialName(value = &quot;Period&quot;)<br>val [periodRaw](period-raw.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [status](status.md) | []<br>@SerialName(value = &quot;Status&quot;)<br>val [status](status.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [type](type.md) | []<br>val [type](type.md): [StaqCardLimitType](../-staq-card-limit-type/index.md)? |
| [typeRaw](type-raw.md) | []<br>@SerialName(value = &quot;Type&quot;)<br>val [typeRaw](type-raw.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
