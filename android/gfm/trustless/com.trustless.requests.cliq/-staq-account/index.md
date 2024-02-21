//[trustless](../../../index.md)/[com.trustless.requests.cliq](../index.md)/[StaqAccount](index.md)

# StaqAccount

[kotlin]\
@Serializable

data class [StaqAccount](index.md)(val currency: String, val openingDate: String, val closingDate: String, val iban: String, val isDefault: Boolean)

Account object

## Constructors

| | |
|---|---|
| [StaqAccount](-staq-account.md) | [kotlin]<br>constructor(currency: String, openingDate: String, closingDate: String, iban: String, isDefault: Boolean) |

## Properties

| Name | Summary |
|---|---|
| [closingDate](closing-date.md) | [kotlin]<br>@SerialName(value = &quot;ClosingDate&quot;)<br>val [closingDate](closing-date.md): String<br>Cliq Account closing date |
| [currency](currency.md) | [kotlin]<br>@SerialName(value = &quot;Currency&quot;)<br>val [currency](currency.md): String<br>Cliq Account currency |
| [iban](iban.md) | [kotlin]<br>@SerialName(value = &quot;Iban&quot;)<br>val [iban](iban.md): String<br>Cliq Account IBAN |
| [isDefault](is-default.md) | [kotlin]<br>@SerialName(value = &quot;IsDefault&quot;)<br>val [isDefault](is-default.md): Boolean<br>The field shows if the account is default by default for the alias |
| [openingDate](opening-date.md) | [kotlin]<br>@SerialName(value = &quot;OpeningDate&quot;)<br>val [openingDate](opening-date.md): String<br>Cliq Account opening date |
