//[trustless](../../../index.md)/[com.trustless.requests.cards.createCard](../index.md)/[CreditDetails](index.md)

# CreditDetails

class [CreditDetails](index.md)(accountNumber: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), amount: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) : [JSONParamsBuilder](../../com.trustless.params/-j-s-o-n-params-builder/index.md)

Optional Parameter for [CreateCardParams](../-create-card-params/index.md) class

#### Parameters

kotlin

| | |
|---|---|
| accountNumber | Bank Account number to be used as a source of funds for the card. Account should have sufficient balance if Amount field is greater than 0 (zero). |
| amount | to be credited to the card right after the card is created. You should specify 0 (zero) Amount if top-up is not required. MAXIMUM: 1000000000000000000 MINIMUM: 0 |

#### Throws

| |
|---|
| [TrustlessAmountException](../../com.trustless.exceptions/-trustless-amount-exception/index.md) |

## Constructors

| | |
|---|---|
| [CreditDetails](-credit-details.md) | [kotlin]<br>constructor(accountNumber: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), amount: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) |
