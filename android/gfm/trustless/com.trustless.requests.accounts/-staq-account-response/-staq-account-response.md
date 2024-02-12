//[trustless](../../../index.md)/[com.trustless.requests.accounts](../index.md)/[StaqAccountResponse](index.md)/[StaqAccountResponse](-staq-account-response.md)

# StaqAccountResponse

[kotlin]\
constructor(branch: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), number: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), typeRaw: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), alternateNumber: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), iban: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), swift: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), bankName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), customer: [StaqCustomer](../-staq-customer/index.md), currencyCode: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), noDebit: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), noCredit: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), dormant: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), currentBalance: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), localCurrencyCurrentBalance: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), blockedAmount: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 0.0, availableBalance: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))

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