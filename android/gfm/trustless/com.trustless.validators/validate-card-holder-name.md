//[trustless](../../index.md)/[com.trustless.validators](index.md)/[validateCardHolderName](validate-card-holder-name.md)

# validateCardHolderName

[kotlin]\
fun [validateCardHolderName](validate-card-holder-name.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))

Validates a cardholder's name and throws TrustlessCardholderNameException if the name does not meet the validation criteria.

#### Parameters

kotlin

| | |
|---|---|
| name | The cardholder's name to validate. |

#### Throws

| | |
|---|---|
| [TrustlessCardholderNameException](../com.trustless.exceptions/-trustless-cardholder-name-exception/index.md) | if the name is invalid. |
