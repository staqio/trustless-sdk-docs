//[trustless](../../../../index.md)/[com.trustless.requests.cards.createCard](../../index.md)/[CreateCardParams](../index.md)/[Builder](index.md)

# Builder

class [Builder](index.md)(currency: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))

Builder to initiate [CreateCardParams](../index.md)

#### Throws

| |
|---|
| [TrustlessCurrencyCodeException](../../../com.trustless.exceptions/-trustless-currency-code-exception/index.md) |
| [TrustlessCardholderNameException](../../../com.trustless.exceptions/-trustless-cardholder-name-exception/index.md) |
| [TrustlessMobileNumberException](../../../com.trustless.exceptions/-trustless-mobile-number-exception/index.md) |

## Constructors

| | |
|---|---|
| [Builder](-builder.md) | <br>constructor(currency: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |

## Functions

| Name | Summary |
|---|---|
| [build](build.md) | <br>fun [build](build.md)(): [CreateCardParams](../index.md) |
| [cardHolderName](card-holder-name.md) | <br>fun [cardHolderName](card-holder-name.md)(cardHolderName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?): [CreateCardParams.Builder](index.md) |
| [creditDetails](credit-details.md) | <br>fun [creditDetails](credit-details.md)(creditDetails: [CreditDetails](../../-credit-details/index.md)?): [CreateCardParams.Builder](index.md) |
| [mobileNumber](mobile-number.md) | <br>fun [mobileNumber](mobile-number.md)(mobileNumber: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?): [CreateCardParams.Builder](index.md) |
