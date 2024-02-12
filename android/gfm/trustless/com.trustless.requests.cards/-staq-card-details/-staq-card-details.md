//[trustless](../../../index.md)/[com.trustless.requests.cards](../index.md)/[StaqCardDetails](index.md)/[StaqCardDetails](-staq-card-details.md)

# StaqCardDetails

[kotlin]\
constructor(typeRaw: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), statusRaw: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), balances: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[StaqCardBalance](../-staq-card-balance/index.md)&gt;, expiryDate: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), token: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), secure3DEnrolled: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null, cvv: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, pan: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), cardHolderName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, mobileNumber: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null)

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
