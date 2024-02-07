//[trustless](../../../index.md)/[com.trustless.requests.cards](../index.md)/[StaqCardBalance](index.md)

# StaqCardBalance

[]\
@Serializable

data class [StaqCardBalance](index.md)(val currencyCode: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val currentBalance: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), val blockedBalance: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), val availableBalance: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))

## Constructors

| | |
|---|---|
| [StaqCardBalance](-staq-card-balance.md) | []<br>constructor(currencyCode: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), currentBalance: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), blockedBalance: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), availableBalance: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) |

## Properties

| Name | Summary |
|---|---|
| [availableBalance](available-balance.md) | []<br>@SerialName(value = &quot;AvailableBalance&quot;)<br>val [availableBalance](available-balance.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [blockedBalance](blocked-balance.md) | []<br>@SerialName(value = &quot;BlockedBalance&quot;)<br>val [blockedBalance](blocked-balance.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [currencyCode](currency-code.md) | []<br>@SerialName(value = &quot;CurrencyCode&quot;)<br>val [currencyCode](currency-code.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [currentBalance](current-balance.md) | []<br>@SerialName(value = &quot;CurrentBalance&quot;)<br>val [currentBalance](current-balance.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
