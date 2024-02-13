//[trustless](../../../index.md)/[com.trustless.requests.cards](../index.md)/[StaqCardTransaction](index.md)

# StaqCardTransaction

[kotlin]\
@Serializable

data class [StaqCardTransaction](index.md)

Card transaction object.

## Properties

| Name | Summary |
|---|---|
| [availableBalance](available-balance.md) | [kotlin]<br>@SerialName(value = &quot;AvailableBalance&quot;)<br>val [availableBalance](available-balance.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Available balance in the card currency after the transaction |
| [blockedAmount](blocked-amount.md) | [kotlin]<br>@SerialName(value = &quot;BlockedAmount&quot;)<br>val [blockedAmount](blocked-amount.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Blocked amount in the card currency |
| [cardCurrency](card-currency.md) | [kotlin]<br>@SerialName(value = &quot;CardCurrency&quot;)<br>val [cardCurrency](card-currency.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>Character ISO code for card currency (e.g. &quot;JOD&quot;, &quot;USD&quot;, &quot;EUR&quot;) |
| [cardCurrencyAmount](card-currency-amount.md) | [kotlin]<br>@SerialName(value = &quot;CardCurrencyAmount&quot;)<br>val [cardCurrencyAmount](card-currency-amount.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Transaction amount in the card currency |
| [cardCurrencyISO](card-currency-i-s-o.md) | [kotlin]<br>@SerialName(value = &quot;CardCurrencyISO&quot;)<br>val [cardCurrencyISO](card-currency-i-s-o.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>Numeric ISO code for card currency (e.g. &quot;400&quot;, &quot;840&quot;, &quot;978&quot;) |
| [date](date.md) | [kotlin]<br>@SerialName(value = &quot;Date&quot;)<br>val [date](date.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>Transaction date and time |
| [debitCreditIndicator](debit-credit-indicator.md) | [kotlin]<br>@SerialName(value = &quot;DebitCreditIndicator&quot;)<br>val [debitCreditIndicator](debit-credit-indicator.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>Indicator of the transaction side. (D)ebit or (C)redit |
| [description](description.md) | [kotlin]<br>@SerialName(value = &quot;Description&quot;)<br>val [description](description.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>Transaction additional information |
| [fees](fees.md) | [kotlin]<br>@SerialName(value = &quot;Fees&quot;)<br>val [fees](fees.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Fees amount in the card currency |
| [id](id.md) | [kotlin]<br>@SerialName(value = &quot;Id&quot;)<br>val [id](id.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>The unique transaction id |
| [mcc](mcc.md) | [kotlin]<br>@SerialName(value = &quot;MCC&quot;)<br>val [mcc](mcc.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null<br>MCC associated with the transaction |
| [merchantCity](merchant-city.md) | [kotlin]<br>@SerialName(value = &quot;MerchantCity&quot;)<br>val [merchantCity](merchant-city.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null<br>Merchant City associated with the transaction |
| [merchantCountry](merchant-country.md) | [kotlin]<br>@SerialName(value = &quot;MerchantCountry&quot;)<br>val [merchantCountry](merchant-country.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null<br>Merchant Country associated with the transaction |
| [merchantName](merchant-name.md) | [kotlin]<br>@SerialName(value = &quot;MerchantName&quot;)<br>val [merchantName](merchant-name.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null<br>Merchant Name associated with the transaction |
| [note](note.md) | [kotlin]<br>@SerialName(value = &quot;Note&quot;)<br>val [note](note.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>Transaction note |
| [pendingAmount](pending-amount.md) | [kotlin]<br>@SerialName(value = &quot;PendingAmount&quot;)<br>val [pendingAmount](pending-amount.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Pending amount in the card currency |
| [postedAmount](posted-amount.md) | [kotlin]<br>@SerialName(value = &quot;PostedAmount&quot;)<br>val [postedAmount](posted-amount.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Actually posted amount in the card currency |
| [status](status.md) | [kotlin]<br>@SerialName(value = &quot;Status&quot;)<br>val [status](status.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>Transaction status |
| [transactionAmount](transaction-amount.md) | [kotlin]<br>@SerialName(value = &quot;TransactionAmount&quot;)<br>val [transactionAmount](transaction-amount.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Transaction amount in the transaction currency |
| [transactionCurrency](transaction-currency.md) | [kotlin]<br>@SerialName(value = &quot;TransactionCurrency&quot;)<br>val [transactionCurrency](transaction-currency.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>Transaction currency |
| [transactionCurrencySymbol](transaction-currency-symbol.md) | [kotlin]<br>@SerialName(value = &quot;TransactionCurrencySymbol&quot;)<br>val [transactionCurrencySymbol](transaction-currency-symbol.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>Transaction currency symbol (e.g. &quot;$&quot;&quot;, &quot;£&quot;) |
| [type](type.md) | [kotlin]<br>@SerialName(value = &quot;Type&quot;)<br>val [type](type.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>Transaction type |
