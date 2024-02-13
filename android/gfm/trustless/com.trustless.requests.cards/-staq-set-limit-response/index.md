//[trustless](../../../index.md)/[com.trustless.requests.cards](../index.md)/[StaqSetLimitResponse](index.md)

# StaqSetLimitResponse

[kotlin]\
@Serializable

data class [StaqSetLimitResponse](index.md)(val periodRaw: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val typeRaw: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val limit: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), val status: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))

Set limit response

## Constructors

| | |
|---|---|
| [StaqSetLimitResponse](-staq-set-limit-response.md) | [kotlin]<br>constructor(periodRaw: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), typeRaw: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), limit: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), status: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |

## Properties

| Name | Summary |
|---|---|
| [limit](limit.md) | [kotlin]<br>@SerialName(value = &quot;Limit&quot;)<br>val [limit](limit.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Limit amount |
| [period](period.md) | [kotlin]<br>val [period](period.md): [StaqCardLimitPeriod](../-staq-card-limit-period/index.md)?<br>Enum variant of [periodRaw](period-raw.md) |
| [periodRaw](period-raw.md) | [kotlin]<br>@SerialName(value = &quot;Period&quot;)<br>val [periodRaw](period-raw.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>Limit period DEFAULT: daily ENUM:  daily, weekly, monthly, annually |
| [status](status.md) | [kotlin]<br>@SerialName(value = &quot;Status&quot;)<br>val [status](status.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>Limit period |
| [type](type.md) | [kotlin]<br>val [type](type.md): [StaqCardLimitType](../-staq-card-limit-type/index.md)?<br>Enum variant of [typeRaw](type-raw.md) |
| [typeRaw](type-raw.md) | [kotlin]<br>@SerialName(value = &quot;Type&quot;)<br>val [typeRaw](type-raw.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>Limit type indicator (ATM or E-Commerce authorizations) ENUM:  Cash, ECommerce |
