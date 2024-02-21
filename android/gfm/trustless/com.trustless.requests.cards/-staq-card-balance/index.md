//[trustless](../../../index.md)/[com.trustless.requests.cards](../index.md)/[StaqCardBalance](index.md)

# StaqCardBalance

[kotlin]\
@Serializable

data class [StaqCardBalance](index.md)

Balance of the card object

## Properties

| Name | Summary |
|---|---|
| [availableBalance](available-balance.md) | [kotlin]<br>@SerialName(value = &quot;AvailableBalance&quot;)<br>val [availableBalance](available-balance.md): Double<br>The amount that can used for authorizations |
| [blockedBalance](blocked-balance.md) | [kotlin]<br>@SerialName(value = &quot;BlockedBalance&quot;)<br>val [blockedBalance](blocked-balance.md): Double<br>The amount authorized but not settled yet |
| [currencyCode](currency-code.md) | [kotlin]<br>@SerialName(value = &quot;CurrencyCode&quot;)<br>val [currencyCode](currency-code.md): String<br>Currency code of the card |
| [currentBalance](current-balance.md) | [kotlin]<br>@SerialName(value = &quot;CurrentBalance&quot;)<br>val [currentBalance](current-balance.md): Double<br>The amount that card balance indicates |
