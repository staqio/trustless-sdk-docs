//[trustless](../../../index.md)/[com.trustless.requests.accounts](../index.md)/[StaqAccountTransaction](index.md)

# StaqAccountTransaction

[kotlin]\
@Serializable

data class [StaqAccountTransaction](index.md)(val date: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val valueDate: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val description: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val debitCreditIndicator: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val transactionAmount: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), val transactionCurrency: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))

## Constructors

| | |
|---|---|
| [StaqAccountTransaction](-staq-account-transaction.md) | [kotlin]<br>constructor(date: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), valueDate: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), description: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), debitCreditIndicator: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), transactionAmount: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), transactionCurrency: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |

## Properties

| Name | Summary |
|---|---|
| [date](date.md) | [kotlin]<br>@SerialName(value = &quot;Date&quot;)<br>val [date](date.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [debitCreditIndicator](debit-credit-indicator.md) | [kotlin]<br>@SerialName(value = &quot;DebitCreditIndicator&quot;)<br>val [debitCreditIndicator](debit-credit-indicator.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [description](description.md) | [kotlin]<br>@SerialName(value = &quot;Description&quot;)<br>val [description](description.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [transactionAmount](transaction-amount.md) | [kotlin]<br>@SerialName(value = &quot;TransactionAmount&quot;)<br>val [transactionAmount](transaction-amount.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [transactionCurrency](transaction-currency.md) | [kotlin]<br>@SerialName(value = &quot;TransactionCurrency&quot;)<br>val [transactionCurrency](transaction-currency.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [valueDate](value-date.md) | [kotlin]<br>@SerialName(value = &quot;ValueDate&quot;)<br>val [valueDate](value-date.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
