//[trustless](../../../index.md)/[com.trustless.requests.accounts](../index.md)/[StaqAccountTransaction](index.md)

# StaqAccountTransaction

[kotlin]\
@Serializable

data class [StaqAccountTransaction](index.md)

Transaction object.

## Properties

| Name | Summary |
|---|---|
| [date](date.md) | [kotlin]<br>@SerialName(value = &quot;Date&quot;)<br>val [date](date.md): String<br>Transaction date |
| [debitCreditIndicator](debit-credit-indicator.md) | [kotlin]<br>@SerialName(value = &quot;DebitCreditIndicator&quot;)<br>val [debitCreditIndicator](debit-credit-indicator.md): String<br>Indicator of the transaction side. (D) for debit or (C) for credit |
| [description](description.md) | [kotlin]<br>@SerialName(value = &quot;Description&quot;)<br>val [description](description.md): String<br>Transaction description |
| [transactionAmount](transaction-amount.md) | [kotlin]<br>@SerialName(value = &quot;TransactionAmount&quot;)<br>val [transactionAmount](transaction-amount.md): Double<br>Transaction amount |
| [transactionCurrency](transaction-currency.md) | [kotlin]<br>@SerialName(value = &quot;TransactionCurrency&quot;)<br>val [transactionCurrency](transaction-currency.md): String<br>Transaction currency code |
| [valueDate](value-date.md) | [kotlin]<br>@SerialName(value = &quot;ValueDate&quot;)<br>val [valueDate](value-date.md): String<br>Transaction value date |
