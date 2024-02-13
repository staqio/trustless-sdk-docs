//[trustless](../../../index.md)/[com.trustless.requests.cards](../index.md)/[StaqChangeCardStatusResponse](index.md)

# StaqChangeCardStatusResponse

[kotlin]\
@Serializable

data class [StaqChangeCardStatusResponse](index.md)(val statusRaw: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))

Change card status response

## Constructors

| | |
|---|---|
| [StaqChangeCardStatusResponse](-staq-change-card-status-response.md) | [kotlin]<br>constructor(statusRaw: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |

## Properties

| Name | Summary |
|---|---|
| [status](status.md) | [kotlin]<br>val [status](status.md): [StaqStatusType](../-staq-status-type/index.md)?<br>enum variant of [statusRaw](status-raw.md) |
| [statusRaw](status-raw.md) | [kotlin]<br>@SerialName(value = &quot;Status&quot;)<br>val [statusRaw](status-raw.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>Status to be assigned to the card ENUM:  ACTIVATED, FROZEN, CLOSED |
