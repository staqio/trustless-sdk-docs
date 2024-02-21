//[trustless](../../../index.md)/[com.trustless.requests.cards](../index.md)/[StaqSetLimitResponse](index.md)

# StaqSetLimitResponse

[kotlin]\
@Serializable

data class [StaqSetLimitResponse](index.md)

Set limit response

## Properties

| Name | Summary |
|---|---|
| [limit](limit.md) | [kotlin]<br>@SerialName(value = &quot;Limit&quot;)<br>val [limit](limit.md): Double<br>Limit amount |
| [period](period.md) | [kotlin]<br>val [period](period.md): [StaqCardLimitPeriod](../-staq-card-limit-period/index.md)?<br>Enum variant of [periodRaw](period-raw.md) |
| [periodRaw](period-raw.md) | [kotlin]<br>@SerialName(value = &quot;Period&quot;)<br>val [periodRaw](period-raw.md): String<br>Limit period DEFAULT: daily ENUM:  daily, weekly, monthly, annually |
| [status](status.md) | [kotlin]<br>@SerialName(value = &quot;Status&quot;)<br>val [status](status.md): String<br>Limit period |
| [type](type.md) | [kotlin]<br>val [type](type.md): [StaqCardLimitType](../-staq-card-limit-type/index.md)?<br>Enum variant of [typeRaw](type-raw.md) |
| [typeRaw](type-raw.md) | [kotlin]<br>@SerialName(value = &quot;Type&quot;)<br>val [typeRaw](type-raw.md): String<br>Limit type indicator (ATM or E-Commerce authorizations) ENUM:  Cash, ECommerce |
