//[trustless](../../../index.md)/[com.trustless.requests.accounts](../index.md)/[StaqAccountResponse](index.md)

# StaqAccountResponse

@Serializable

data class [StaqAccountResponse](index.md)(val branch: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val number: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val typeRaw: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val alternateNumber: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, val name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val iban: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val swift: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val bankName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val customer: [StaqCustomer](../-staq-customer/index.md), val currencyCode: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val noDebit: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), val noCredit: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), val dormant: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), val currentBalance: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), val localCurrencyCurrentBalance: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), val blockedAmount: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 0.0, val availableBalance: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))

#### Parameters

kotlin

| | |
|---|---|
| branch | The code of the Bank branch that holds the account |
| number | Number |
| alternateNumber | Alternate account number |
| name | Account name |
| iban | Account IBAN |
| swift | SWIFT code |
| bankName | Bank name |
| customer | Customer data object |
| currencyCode | The ISO 3 chars code of the account currency |
| noDebit | The indication that account debit is prohibited |
| noCredit | The indication that account credit is prohibited |
| dormant | The indication that account is dormant |
| currentBalance | Account current balance in the account currency |
| localCurrencyCurrentBalance | Account current balance in JOD |
| blockedAmount | Account blocked amount in the account currency |
| availableBalance | Account available balance in the account currency |

## Constructors

| | |
|---|---|
| [StaqAccountResponse](-staq-account-response.md) | [kotlin]<br>constructor(branch: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), number: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), typeRaw: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), alternateNumber: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), iban: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), swift: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), bankName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), customer: [StaqCustomer](../-staq-customer/index.md), currencyCode: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), noDebit: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), noCredit: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), dormant: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), currentBalance: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), localCurrencyCurrentBalance: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), blockedAmount: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 0.0, availableBalance: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) |

## Properties

| Name | Summary |
|---|---|
| [alternateNumber](alternate-number.md) | [kotlin]<br>@SerialName(value = &quot;AlternateNumber&quot;)<br>val [alternateNumber](alternate-number.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [availableBalance](available-balance.md) | [kotlin]<br>@SerialName(value = &quot;AvailableBalance&quot;)<br>val [availableBalance](available-balance.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [bankName](bank-name.md) | [kotlin]<br>@SerialName(value = &quot;BankName&quot;)<br>val [bankName](bank-name.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [blockedAmount](blocked-amount.md) | [kotlin]<br>@SerialName(value = &quot;BlockedAmount&quot;)<br>val [blockedAmount](blocked-amount.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 0.0 |
| [branch](branch.md) | [kotlin]<br>@SerialName(value = &quot;Branch&quot;)<br>val [branch](branch.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [currencyCode](currency-code.md) | [kotlin]<br>@SerialName(value = &quot;CurrencyCode&quot;)<br>val [currencyCode](currency-code.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [currentBalance](current-balance.md) | [kotlin]<br>@SerialName(value = &quot;CurrentBalance&quot;)<br>val [currentBalance](current-balance.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [customer](customer.md) | [kotlin]<br>@SerialName(value = &quot;Customer&quot;)<br>val [customer](customer.md): [StaqCustomer](../-staq-customer/index.md) |
| [dormant](dormant.md) | [kotlin]<br>@SerialName(value = &quot;Dormant&quot;)<br>val [dormant](dormant.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [iban](iban.md) | [kotlin]<br>@SerialName(value = &quot;IBAN&quot;)<br>val [iban](iban.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [localCurrencyCurrentBalance](local-currency-current-balance.md) | [kotlin]<br>@SerialName(value = &quot;LocalCurrencyCurrentBalance&quot;)<br>val [localCurrencyCurrentBalance](local-currency-current-balance.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [name](name.md) | [kotlin]<br>@SerialName(value = &quot;Name&quot;)<br>val [name](name.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [noCredit](no-credit.md) | [kotlin]<br>@SerialName(value = &quot;NoCredit&quot;)<br>val [noCredit](no-credit.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [noDebit](no-debit.md) | [kotlin]<br>@SerialName(value = &quot;NoDebit&quot;)<br>val [noDebit](no-debit.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [number](number.md) | [kotlin]<br>@SerialName(value = &quot;Number&quot;)<br>val [number](number.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [swift](swift.md) | [kotlin]<br>@SerialName(value = &quot;SWIFT&quot;)<br>val [swift](swift.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [typeRaw](type-raw.md) | [kotlin]<br>@SerialName(value = &quot;Type&quot;)<br>val [typeRaw](type-raw.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
