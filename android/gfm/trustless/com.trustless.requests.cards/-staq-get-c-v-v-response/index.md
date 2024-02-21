//[trustless](../../../index.md)/[com.trustless.requests.cards](../index.md)/[StaqGetCVVResponse](index.md)

# StaqGetCVVResponse

[kotlin]\
@Serializable

data class [StaqGetCVVResponse](index.md)

Get Pan with CVV Response

## Properties

| Name | Summary |
|---|---|
| [cvv](cvv.md) | [kotlin]<br>@SerialName(value = &quot;CVV&quot;)<br>val [cvv](cvv.md): String<br>CVV code required for the card authorization (sensitive information) MAXLENGTH: 3 MINLENGTH: 3 |
| [pan](pan.md) | [kotlin]<br>@SerialName(value = &quot;PAN&quot;)<br>val [pan](pan.md): String<br>Full unmasked card number (sensitive information) |
| [token](token.md) | [kotlin]<br>@SerialName(value = &quot;Token&quot;)<br>val [token](token.md): String<br>The unique card identifier (non-sensitive information) |
