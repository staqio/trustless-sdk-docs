//[trustless](../../../index.md)/[com.trustless.requests.cards](../index.md)/[StaqLimitEntry](index.md)

# StaqLimitEntry

@Serializable

data class [StaqLimitEntry](index.md)(val limit: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), val transactionCountLimit: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), val transactionAmountLimit: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), val remainingAmount: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)? = null, val remainingCount: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)? = null)

Limit entry

#### Parameters

kotlin

| | |
|---|---|
| limit | Maximum limit amount |
| transactionCountLimit | Maximum number of transactions |
| transactionAmountLimit | Maximum single transaction amount |
| remainingAmount | Remaining Amount Limit |
| remainingCount | Remainig Count Limit |

## Constructors

| | |
|---|---|
| [StaqLimitEntry](-staq-limit-entry.md) | [kotlin]<br>constructor(limit: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), transactionCountLimit: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), transactionAmountLimit: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), remainingAmount: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)? = null, remainingCount: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)? = null) |

## Properties

| Name | Summary |
|---|---|
| [limit](limit.md) | [kotlin]<br>@SerialName(value = &quot;Limit&quot;)<br>val [limit](limit.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [remainingAmount](remaining-amount.md) | [kotlin]<br>@SerialName(value = &quot;RemainingAmount&quot;)<br>val [remainingAmount](remaining-amount.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)? = null |
| [remainingCount](remaining-count.md) | [kotlin]<br>@SerialName(value = &quot;RemainingCount&quot;)<br>val [remainingCount](remaining-count.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)? = null |
| [transactionAmountLimit](transaction-amount-limit.md) | [kotlin]<br>@SerialName(value = &quot;TransactionAmountLimit&quot;)<br>val [transactionAmountLimit](transaction-amount-limit.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [transactionCountLimit](transaction-count-limit.md) | [kotlin]<br>@SerialName(value = &quot;TransactionCountLimit&quot;)<br>val [transactionCountLimit](transaction-count-limit.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
