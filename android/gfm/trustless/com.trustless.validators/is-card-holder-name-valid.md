//[trustless](../../index.md)/[com.trustless.validators](index.md)/[isCardHolderNameValid](is-card-holder-name-valid.md)

# isCardHolderNameValid

[kotlin]\
fun [isCardHolderNameValid](is-card-holder-name-valid.md)(name: String): Boolean

Checks if the card holder's name length is less than or equal to 22 characters, and if it matches the regex pattern ^(A-Z'.-+\s?)+$ which allows uppercase letters, apostrophes, periods, hyphens, and spaces.
