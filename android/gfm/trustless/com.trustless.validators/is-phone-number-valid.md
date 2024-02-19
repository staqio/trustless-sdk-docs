//[trustless](../../index.md)/[com.trustless.validators](index.md)/[isPhoneNumberValid](is-phone-number-valid.md)

# isPhoneNumberValid

[kotlin]\
fun [isPhoneNumberValid](is-phone-number-valid.md)(number: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)

Validates a phone number by checking if its length is between 4 and 16 characters and if it matches the regex pattern ^\\+0-9*$, which requires the number to start with a '+' followed by a non-zero digit and then any sequence of digits, ensuring it is an international format.
