//[trustless](../../../index.md)/[com.trustless.requests.cliq](../index.md)/[StaqCreateAlias](index.md)

# StaqCreateAlias

[kotlin]\
@Serializable

data class [StaqCreateAlias](index.md)(val iban: String, val alias: String, val isDefault: Boolean)

Create alias object

## Constructors

| | |
|---|---|
| [StaqCreateAlias](-staq-create-alias.md) | [kotlin]<br>constructor(iban: String, alias: String, isDefault: Boolean) |

## Properties

| Name | Summary |
|---|---|
| [alias](alias.md) | [kotlin]<br>@SerialName(value = &quot;Alias&quot;)<br>val [alias](alias.md): String |
| [iban](iban.md) | [kotlin]<br>@SerialName(value = &quot;Iban&quot;)<br>val [iban](iban.md): String |
| [isDefault](is-default.md) | [kotlin]<br>@SerialName(value = &quot;IsDefault&quot;)<br>val [isDefault](is-default.md): Boolean |
