//[trustless](../../../index.md)/[com.trustless.requests.cards](../index.md)/[StaqGetLimitResponse](index.md)

# StaqGetLimitResponse

@Serializable

data class [StaqGetLimitResponse](index.md)(val weekly: [StaqLimitGroup](../-staq-limit-group/index.md), val daily: [StaqLimitGroup](../-staq-limit-group/index.md), val monthly: [StaqLimitGroup](../-staq-limit-group/index.md), val annual: [StaqLimitGroup](../-staq-limit-group/index.md))

Get limit response

#### Parameters

kotlin

| | |
|---|---|
| weekly | Weekly limit group |
| daily | Daily limit group |
| monthly | Monthly limit group |
| annual | Annual limit group |

## Constructors

| | |
|---|---|
| [StaqGetLimitResponse](-staq-get-limit-response.md) | [kotlin]<br>constructor(weekly: [StaqLimitGroup](../-staq-limit-group/index.md), daily: [StaqLimitGroup](../-staq-limit-group/index.md), monthly: [StaqLimitGroup](../-staq-limit-group/index.md), annual: [StaqLimitGroup](../-staq-limit-group/index.md)) |

## Properties

| Name | Summary |
|---|---|
| [annual](annual.md) | [kotlin]<br>@SerialName(value = &quot;Annual&quot;)<br>val [annual](annual.md): [StaqLimitGroup](../-staq-limit-group/index.md) |
| [daily](daily.md) | [kotlin]<br>@SerialName(value = &quot;Daily&quot;)<br>val [daily](daily.md): [StaqLimitGroup](../-staq-limit-group/index.md) |
| [monthly](monthly.md) | [kotlin]<br>@SerialName(value = &quot;Monthly&quot;)<br>val [monthly](monthly.md): [StaqLimitGroup](../-staq-limit-group/index.md) |
| [weekly](weekly.md) | [kotlin]<br>@SerialName(value = &quot;Weekly&quot;)<br>val [weekly](weekly.md): [StaqLimitGroup](../-staq-limit-group/index.md) |
