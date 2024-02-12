//[trustless](../../../index.md)/[com.trustless.requests.cards](../index.md)/[StaqCardDetails](index.md)

# StaqCardDetails

@Serializable

data class [StaqCardDetails](index.md)(val typeRaw: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val statusRaw: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val balances: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[StaqCardBalance](../-staq-card-balance/index.md)&gt;, val expiryDate: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val token: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val secure3DEnrolled: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null, val cvv: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, val pan: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val cardHolderName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, val mobileNumber: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null)

Card Details for card.

#### Parameters

kotlin

| | |
|---|---|
| typeRaw | Virtual or physical card indication (e.g. &quot;virtual&quot;, &quot;physical&quot;) ENUM:  VIRTUAL, PHYSICAL |
| statusRaw | Card current status |
| balances | array of balances |
| expiryDate | Expiry month and year of the card in the format MMYY (e.g. &quot;0822&quot;) |
| token | The unique card identifier (not sensitive) |
| secure3DEnrolled | 3DS enrollment status |
| cvv | CVV/CVC code of the card MAXLENGTH: 3 MINLENGTH: 3 |
| pan | Card number |
| cardHolderName | Cardholder name |

## Constructors

| | |
|---|---|
| [StaqCardDetails](-staq-card-details.md) | [kotlin]<br>constructor(typeRaw: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), statusRaw: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), balances: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[StaqCardBalance](../-staq-card-balance/index.md)&gt;, expiryDate: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), token: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), secure3DEnrolled: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null, cvv: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, pan: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), cardHolderName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, mobileNumber: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null) |

## Properties

| Name | Summary |
|---|---|
| [balances](balances.md) | [kotlin]<br>@SerialName(value = &quot;Balances&quot;)<br>val [balances](balances.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[StaqCardBalance](../-staq-card-balance/index.md)&gt; |
| [cardHolderName](card-holder-name.md) | [kotlin]<br>@SerialName(value = &quot;CardHolderName&quot;)<br>val [cardHolderName](card-holder-name.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [cvv](cvv.md) | [kotlin]<br>@SerialName(value = &quot;CVV&quot;)<br>val [cvv](cvv.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [expiryDate](expiry-date.md) | [kotlin]<br>@SerialName(value = &quot;ExpiryDate&quot;)<br>val [expiryDate](expiry-date.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [mobileNumber](mobile-number.md) | [kotlin]<br>@SerialName(value = &quot;MobileNumber&quot;)<br>val [mobileNumber](mobile-number.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [pan](pan.md) | [kotlin]<br>@SerialName(value = &quot;PAN&quot;)<br>val [pan](pan.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [secure3DEnrolled](secure3-d-enrolled.md) | [kotlin]<br>@SerialName(value = &quot;Secure3DEnrolled&quot;)<br>val [secure3DEnrolled](secure3-d-enrolled.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null |
| [status](status.md) | [kotlin]<br>val [status](status.md): [StaqStatusType](../-staq-status-type/index.md)?<br>enum type of a statusRaw property ENUM:  ACTIVATED, FROZEN, CLOSED |
| [statusRaw](status-raw.md) | [kotlin]<br>@SerialName(value = &quot;Status&quot;)<br>val [statusRaw](status-raw.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [token](token.md) | [kotlin]<br>@SerialName(value = &quot;Token&quot;)<br>val [token](token.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [type](type.md) | [kotlin]<br>val [type](type.md): [StaqCardType](../-staq-card-type/index.md)?<br>enum type of a typeRaw property |
| [typeRaw](type-raw.md) | [kotlin]<br>@SerialName(value = &quot;Type&quot;)<br>val [typeRaw](type-raw.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
