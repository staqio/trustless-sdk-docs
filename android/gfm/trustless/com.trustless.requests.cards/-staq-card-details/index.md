//[trustless](../../../index.md)/[com.trustless.requests.cards](../index.md)/[StaqCardDetails](index.md)

# StaqCardDetails

\
@Serializable

data class [StaqCardDetails](index.md)(val typeRaw: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val statusRaw: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val balances: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[StaqCardBalance](../-staq-card-balance/index.md)&gt;, val expiryDate: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val token: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val secure3DEnrolled: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null, val cvv: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, val pan: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val cardHolderName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, val mobileNumber: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null)

## Constructors

| | |
|---|---|
| [StaqCardDetails](-staq-card-details.md) | <br>constructor(typeRaw: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), statusRaw: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), balances: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[StaqCardBalance](../-staq-card-balance/index.md)&gt;, expiryDate: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), token: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), secure3DEnrolled: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null, cvv: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, pan: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), cardHolderName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, mobileNumber: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null) |

## Properties

| Name | Summary |
|---|---|
| [balances](balances.md) | <br>@SerialName(value = &quot;Balances&quot;)<br>val [balances](balances.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[StaqCardBalance](../-staq-card-balance/index.md)&gt; |
| [cardHolderName](card-holder-name.md) | <br>@SerialName(value = &quot;CardHolderName&quot;)<br>val [cardHolderName](card-holder-name.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [cvv](cvv.md) | <br>@SerialName(value = &quot;CVV&quot;)<br>val [cvv](cvv.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [expiryDate](expiry-date.md) | <br>@SerialName(value = &quot;ExpiryDate&quot;)<br>val [expiryDate](expiry-date.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [mobileNumber](mobile-number.md) | <br>@SerialName(value = &quot;MobileNumber&quot;)<br>val [mobileNumber](mobile-number.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [pan](pan.md) | <br>@SerialName(value = &quot;PAN&quot;)<br>val [pan](pan.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [secure3DEnrolled](secure3-d-enrolled.md) | <br>@SerialName(value = &quot;Secure3DEnrolled&quot;)<br>val [secure3DEnrolled](secure3-d-enrolled.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null |
| [status](status.md) | <br>val [status](status.md): [StaqStatusType](../-staq-status-type/index.md)? |
| [statusRaw](status-raw.md) | <br>@SerialName(value = &quot;Status&quot;)<br>val [statusRaw](status-raw.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [token](token.md) | <br>@SerialName(value = &quot;Token&quot;)<br>val [token](token.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [type](type.md) | <br>val [type](type.md): [StaqCardType](../-staq-card-type/index.md)? |
| [typeRaw](type-raw.md) | <br>@SerialName(value = &quot;Type&quot;)<br>val [typeRaw](type-raw.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
