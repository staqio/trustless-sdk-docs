//[trustless](../../../index.md)/[com.trustless.requests.accounts](../index.md)/[StaqAccountTransaction](index.md)

# StaqAccountTransaction

[kotlin]\
@Serializable

data class [StaqAccountTransaction](index.md)

Transaction object.

## Properties

| Name | Summary |
|---|---|
| [date](date.md) | [kotlin]<br>@SerialName(value = &quot;Date&quot;)<br>val [date](date.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>Transaction date |
| [debitCreditIndicator](debit-credit-indicator.md) | [kotlin]<br>@SerialName(value = &quot;DebitCreditIndicator&quot;)<br>val [debitCreditIndicator](debit-credit-indicator.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>Indicator of the transaction side. (D) for debit or (C) for credit |
| [description](description.md) | [kotlin]<br>@SerialName(value = &quot;Description&quot;)<br>val [description](description.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>Transaction description |
| [transactionAmount](transaction-amount.md) | [kotlin]<br>@SerialName(value = &quot;TransactionAmount&quot;)<br>val [transactionAmount](transaction-amount.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Transaction amount |
| [transactionCurrency](transaction-currency.md) | [kotlin]<br>@SerialName(value = &quot;TransactionCurrency&quot;)<br>val [transactionCurrency](transaction-currency.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>Transaction currency code |
| [valueDate](value-date.md) | [kotlin]<br>@SerialName(value = &quot;ValueDate&quot;)<br>val [valueDate](value-date.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>Transaction value date |
