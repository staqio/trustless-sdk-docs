//[trustless](../../../index.md)/[com.trustless.requests.cliq](../index.md)/[StaqAccount](index.md)

# StaqAccount

[kotlin]\
@Serializable

data class [StaqAccount](index.md)(val currency: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val openingDate: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val closingDate: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val iban: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val isDefault: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))

Account object

## Constructors

| | |
|---|---|
| [StaqAccount](-staq-account.md) | [kotlin]<br>constructor(currency: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), openingDate: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), closingDate: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), iban: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), isDefault: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) |

## Properties

| Name | Summary |
|---|---|
| [closingDate](closing-date.md) | [kotlin]<br>@SerialName(value = &quot;ClosingDate&quot;)<br>val [closingDate](closing-date.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>Cliq Account closing date |
| [currency](currency.md) | [kotlin]<br>@SerialName(value = &quot;Currency&quot;)<br>val [currency](currency.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>Cliq Account currency |
| [iban](iban.md) | [kotlin]<br>@SerialName(value = &quot;Iban&quot;)<br>val [iban](iban.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>Cliq Account IBAN |
| [isDefault](is-default.md) | [kotlin]<br>@SerialName(value = &quot;IsDefault&quot;)<br>val [isDefault](is-default.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>The field shows if the account is default by default for the alias |
| [openingDate](opening-date.md) | [kotlin]<br>@SerialName(value = &quot;OpeningDate&quot;)<br>val [openingDate](opening-date.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>Cliq Account opening date |
