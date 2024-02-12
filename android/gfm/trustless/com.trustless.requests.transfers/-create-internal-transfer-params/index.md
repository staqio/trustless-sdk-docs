//[trustless](../../../index.md)/[com.trustless.requests.transfers](../index.md)/[CreateInternalTransferParams](index.md)

# CreateInternalTransferParams

class [CreateInternalTransferParams](index.md)(accountNumber: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), beneficiaryAccount: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), amount: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), currencyCode: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), transferNote: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null) : [JSONParamsBuilder](../../com.trustless.params/-j-s-o-n-params-builder/index.md)

Create internal transfer params

#### Parameters

kotlin

| | |
|---|---|
| accountNumber | Customer Account Number |
| beneficiaryAccount | Beneficiary Account Number |
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
| [CreateInternalTransferParams](-create-internal-transfer-params.md) | [kotlin]<br>constructor(accountNumber: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), beneficiaryAccount: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), amount: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), currencyCode: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), transferNote: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null) |
