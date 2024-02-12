//[trustless](../../../index.md)/[com.trustless.requests.cards](../index.md)/[StaqCardTransaction](index.md)

# StaqCardTransaction

@Serializable

data class [StaqCardTransaction](index.md)(val id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val type: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val status: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val date: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val description: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val transactionCurrency: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val transactionCurrencySymbol: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val transactionAmount: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), val cardCurrencyISO: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val cardCurrency: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val cardCurrencyAmount: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), val fees: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), val availableBalance: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), val postedAmount: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), val blockedAmount: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), val pendingAmount: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), val note: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val debitCreditIndicator: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val mcc: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, val merchantName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, val merchantCity: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, val merchantCountry: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null)

Card transaction object.

#### Parameters

kotlin

| | |
|---|---|
| id | The unique transaction id |
| type | Transaction type |
| status | Transaction status |
| date | Transaction date and time |
| description | Transaction additional information |
| transactionCurrency | Transaction currency |
| transactionCurrencySymbol | Transaction currency symbol (e.g. &quot;$&quot;&quot;, &quot;£&quot;) |
| transactionAmount | Transaction amount in the transaction currency |
| cardCurrencyISO | Numeric ISO code for card currency (e.g. &quot;400&quot;, &quot;840&quot;, &quot;978&quot;) |
| cardCurrency | Character ISO code for card currency (e.g. &quot;JOD&quot;, &quot;USD&quot;, &quot;EUR&quot;) |
| cardCurrencyAmount | Transaction amount in the card currency |
| fees | Fees amount in the card currency |
| availableBalance | Available balance in the card currency after the transaction |
| postedAmount | Actually posted amount in the card currency |
| blockedAmount | Blocked amount in the card currency |
| pendingAmount | Pending amount in the card currency |
| note | Transaction note |
| debitCreditIndicator | Indicator of the transaction side. (D)ebit or (C)redit |
| mcc | MCC associated with the transaction |
| merchantName | Merchant Name associated with the transaction |
| merchantCity | Merchant City associated with the transaction |
| merchantCountry | Merchant Country associated with the transaction |

## Constructors

| | |
|---|---|
| [StaqCardTransaction](-staq-card-transaction.md) | [kotlin]<br>constructor(id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), type: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), status: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), date: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), description: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), transactionCurrency: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), transactionCurrencySymbol: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), transactionAmount: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), cardCurrencyISO: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), cardCurrency: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), cardCurrencyAmount: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), fees: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), availableBalance: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), postedAmount: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), blockedAmount: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), pendingAmount: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), note: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), debitCreditIndicator: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), mcc: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, merchantName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, merchantCity: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, merchantCountry: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null) |

## Properties

| Name | Summary |
|---|---|
| [availableBalance](available-balance.md) | [kotlin]<br>@SerialName(value = &quot;AvailableBalance&quot;)<br>val [availableBalance](available-balance.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [blockedAmount](blocked-amount.md) | [kotlin]<br>@SerialName(value = &quot;BlockedAmount&quot;)<br>val [blockedAmount](blocked-amount.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [cardCurrency](card-currency.md) | [kotlin]<br>@SerialName(value = &quot;CardCurrency&quot;)<br>val [cardCurrency](card-currency.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [cardCurrencyAmount](card-currency-amount.md) | [kotlin]<br>@SerialName(value = &quot;CardCurrencyAmount&quot;)<br>val [cardCurrencyAmount](card-currency-amount.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [cardCurrencyISO](card-currency-i-s-o.md) | [kotlin]<br>@SerialName(value = &quot;CardCurrencyISO&quot;)<br>val [cardCurrencyISO](card-currency-i-s-o.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [date](date.md) | [kotlin]<br>@SerialName(value = &quot;Date&quot;)<br>val [date](date.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [debitCreditIndicator](debit-credit-indicator.md) | [kotlin]<br>@SerialName(value = &quot;DebitCreditIndicator&quot;)<br>val [debitCreditIndicator](debit-credit-indicator.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [description](description.md) | [kotlin]<br>@SerialName(value = &quot;Description&quot;)<br>val [description](description.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [fees](fees.md) | [kotlin]<br>@SerialName(value = &quot;Fees&quot;)<br>val [fees](fees.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [id](id.md) | [kotlin]<br>@SerialName(value = &quot;Id&quot;)<br>val [id](id.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [mcc](mcc.md) | [kotlin]<br>@SerialName(value = &quot;MCC&quot;)<br>val [mcc](mcc.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [merchantCity](merchant-city.md) | [kotlin]<br>@SerialName(value = &quot;MerchantCity&quot;)<br>val [merchantCity](merchant-city.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [merchantCountry](merchant-country.md) | [kotlin]<br>@SerialName(value = &quot;MerchantCountry&quot;)<br>val [merchantCountry](merchant-country.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [merchantName](merchant-name.md) | [kotlin]<br>@SerialName(value = &quot;MerchantName&quot;)<br>val [merchantName](merchant-name.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [note](note.md) | [kotlin]<br>@SerialName(value = &quot;Note&quot;)<br>val [note](note.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [pendingAmount](pending-amount.md) | [kotlin]<br>@SerialName(value = &quot;PendingAmount&quot;)<br>val [pendingAmount](pending-amount.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [postedAmount](posted-amount.md) | [kotlin]<br>@SerialName(value = &quot;PostedAmount&quot;)<br>val [postedAmount](posted-amount.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [status](status.md) | [kotlin]<br>@SerialName(value = &quot;Status&quot;)<br>val [status](status.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [transactionAmount](transaction-amount.md) | [kotlin]<br>@SerialName(value = &quot;TransactionAmount&quot;)<br>val [transactionAmount](transaction-amount.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [transactionCurrency](transaction-currency.md) | [kotlin]<br>@SerialName(value = &quot;TransactionCurrency&quot;)<br>val [transactionCurrency](transaction-currency.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [transactionCurrencySymbol](transaction-currency-symbol.md) | [kotlin]<br>@SerialName(value = &quot;TransactionCurrencySymbol&quot;)<br>val [transactionCurrencySymbol](transaction-currency-symbol.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [type](type.md) | [kotlin]<br>@SerialName(value = &quot;Type&quot;)<br>val [type](type.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |