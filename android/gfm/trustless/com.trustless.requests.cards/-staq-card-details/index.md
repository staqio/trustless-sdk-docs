//[trustless](../../../index.md)/[com.trustless.requests.cards](../index.md)/[StaqCardDetails](index.md)

# StaqCardDetails

[kotlin]\
@Serializable

data class [StaqCardDetails](index.md)

Card Details for card.

## Properties

| Name | Summary |
|---|---|
| [balances](balances.md) | [kotlin]<br>@SerialName(value = &quot;Balances&quot;)<br>val [balances](balances.md): List&lt;[StaqCardBalance](../-staq-card-balance/index.md)&gt;<br>array of balances |
| [cardHolderName](card-holder-name.md) | [kotlin]<br>@SerialName(value = &quot;CardHolderName&quot;)<br>val [cardHolderName](card-holder-name.md): String? = null<br>Cardholder name |
| [cvv](cvv.md) | [kotlin]<br>@SerialName(value = &quot;CVV&quot;)<br>val [cvv](cvv.md): String? = null<br>CVV/CVC code of the card MAXLENGTH: 3 MINLENGTH: 3 |
| [expiryDate](expiry-date.md) | [kotlin]<br>@SerialName(value = &quot;ExpiryDate&quot;)<br>val [expiryDate](expiry-date.md): String<br>Expiry month and year of the card in the format MMYY (e.g. &quot;0822&quot;) |
| [mobileNumber](mobile-number.md) | [kotlin]<br>@SerialName(value = &quot;MobileNumber&quot;)<br>val [mobileNumber](mobile-number.md): String? = null |
| [pan](pan.md) | [kotlin]<br>@SerialName(value = &quot;PAN&quot;)<br>val [pan](pan.md): String<br>Card number |
| [secure3DEnrolled](secure3-d-enrolled.md) | [kotlin]<br>@SerialName(value = &quot;Secure3DEnrolled&quot;)<br>val [secure3DEnrolled](secure3-d-enrolled.md): Boolean? = null<br>3DS enrollment status |
| [status](status.md) | [kotlin]<br>val [status](status.md): [StaqStatusType](../-staq-status-type/index.md)?<br>enum type of a statusRaw property ENUM:  ACTIVATED, FROZEN, CLOSED |
| [statusRaw](status-raw.md) | [kotlin]<br>@SerialName(value = &quot;Status&quot;)<br>val [statusRaw](status-raw.md): String<br>Card current status |
| [token](token.md) | [kotlin]<br>@SerialName(value = &quot;Token&quot;)<br>val [token](token.md): String<br>The unique card identifier (not sensitive) |
| [type](type.md) | [kotlin]<br>val [type](type.md): [StaqCardType](../-staq-card-type/index.md)?<br>enum type of a typeRaw property |
| [typeRaw](type-raw.md) | [kotlin]<br>@SerialName(value = &quot;Type&quot;)<br>val [typeRaw](type-raw.md): String<br>Virtual or physical card indication (e.g. &quot;virtual&quot;, &quot;physical&quot;) ENUM:  VIRTUAL, PHYSICAL |
