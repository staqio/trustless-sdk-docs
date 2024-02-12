//[trustless](../../../index.md)/[com.trustless.requests.transfers](../index.md)/[CreateCliqTransferParams](index.md)

# CreateCliqTransferParams

class [CreateCliqTransferParams](index.md)(accountNumber: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), beneficiaryAliasType: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), beneficiaryAlias: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), amount: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), currencyCode: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), purposeCode: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), transferNote: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null) : [JSONParamsBuilder](../../com.trustless.params/-j-s-o-n-params-builder/index.md)

Create Cliq Transfer params

[Server Api Reference](https://developer.staq.io/docs/apis/transfers#/Transfers/Create%20a%20Cliq%20transfer)

#### Parameters

kotlin

| | |
|---|---|
| accountNumber | Customer Account Number |
| beneficiaryAliasType | Beneficiary Alias Type ENUM:  ALIAS, MOBL |
| beneficiaryAlias | Beneficiary Alias |
| amount | Transfer amount MAXIMUM: 1000000000000000000 MINIMUM: 0.00001 |
| currencyCode | ISO3 Currency code for the card (e.g &quot;JOD&quot;, &quot;USD&quot;, &quot;EUR&quot;) PATTERN: ^A-Z{3}$ |
| transferNote | Transfer note |

#### Throws

| |
|---|
| [TrustlessAmountException](../../com.trustless.exceptions/-trustless-amount-exception/index.md) |
| [TrustlessCurrencyCodeException](../../com.trustless.exceptions/-trustless-currency-code-exception/index.md) |

## Constructors

| | |
|---|---|
| [CreateCliqTransferParams](-create-cliq-transfer-params.md) | [kotlin]<br>constructor(accountNumber: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), beneficiaryAliasType: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), beneficiaryAlias: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), amount: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), currencyCode: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), purposeCode: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), transferNote: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null) |
