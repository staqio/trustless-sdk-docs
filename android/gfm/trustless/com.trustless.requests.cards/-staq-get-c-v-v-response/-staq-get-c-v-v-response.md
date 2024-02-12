//[trustless](../../../index.md)/[com.trustless.requests.cards](../index.md)/[StaqGetCVVResponse](index.md)/[StaqGetCVVResponse](-staq-get-c-v-v-response.md)

# StaqGetCVVResponse

[kotlin]\
constructor(token: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), pan: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), cvv: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))

#### Parameters

kotlin

| | |
|---|---|
| token | The unique card identifier (non-sensitive information) |
| pan | Full unmasked card number (sensitive information) |
| cvv | CVV code required for the card authorization (sensitive information) MAXLENGTH: 3 MINLENGTH: 3 |
