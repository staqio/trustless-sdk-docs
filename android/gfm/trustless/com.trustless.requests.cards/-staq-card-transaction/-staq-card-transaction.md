//[trustless](../../../index.md)/[com.trustless.requests.cards](../index.md)/[StaqCardTransaction](index.md)/[StaqCardTransaction](-staq-card-transaction.md)

# StaqCardTransaction

[kotlin]\
constructor(id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), type: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), status: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), date: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), description: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), transactionCurrency: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), transactionCurrencySymbol: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), transactionAmount: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), cardCurrencyISO: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), cardCurrency: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), cardCurrencyAmount: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), fees: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), availableBalance: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), postedAmount: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), blockedAmount: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), pendingAmount: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), note: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), debitCreditIndicator: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), mcc: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, merchantName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, merchantCity: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, merchantCountry: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null)

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
