//[trustless](../../index.md)/[com.trustless.validators](index.md)/[isCardHolderNameValid](is-card-holder-name-valid.md)

# isCardHolderNameValid

[kotlin]\
fun [isCardHolderNameValid](is-card-holder-name-valid.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)

Checks if the card holder's name length is less than or equal to 22 characters, and if it matches the regex pattern ^(A-Z'.-+\s?)+$ which allows uppercase letters, apostrophes, periods, hyphens, and spaces.
