//[trustless](../../../index.md)/[com.trustless.requests.cards.createCard](../index.md)/[CreditDetails](index.md)/[CreditDetails](-credit-details.md)

# CreditDetails

[kotlin]\
constructor(accountNumber: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), amount: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))

#### Parameters

kotlin

| | |
|---|---|
| accountNumber | Bank Account number to be used as a source of funds for the card. Account should have sufficient balance if Amount field is greater than 0 (zero). |
| amount | to be credited to the card right after the card is created. You should specify 0 (zero) Amount if top-up is not required. MAXIMUM: 1000000000000000000 MINIMUM: 0 |
