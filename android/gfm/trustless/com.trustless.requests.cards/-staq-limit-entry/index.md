//[trustless](../../../index.md)/[com.trustless.requests.cards](../index.md)/[StaqLimitEntry](index.md)

# StaqLimitEntry

[kotlin]\
@Serializable

data class [StaqLimitEntry](index.md)(val limit: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), val transactionCountLimit: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), val transactionAmountLimit: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), val remainingAmount: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)? = null, val remainingCount: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)? = null)

Limit entry

## Constructors

| | |
|---|---|
| [StaqLimitEntry](-staq-limit-entry.md) | [kotlin]<br>constructor(limit: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), transactionCountLimit: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), transactionAmountLimit: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), remainingAmount: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)? = null, remainingCount: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)? = null) |

## Properties

| Name | Summary |
|---|---|
| [limit](limit.md) | [kotlin]<br>@SerialName(value = &quot;Limit&quot;)<br>val [limit](limit.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Maximum limit amount |
| [remainingAmount](remaining-amount.md) | [kotlin]<br>@SerialName(value = &quot;RemainingAmount&quot;)<br>val [remainingAmount](remaining-amount.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)? = null<br>Remaining Amount Limit |
| [remainingCount](remaining-count.md) | [kotlin]<br>@SerialName(value = &quot;RemainingCount&quot;)<br>val [remainingCount](remaining-count.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)? = null<br>Remainig Count Limit |
| [transactionAmountLimit](transaction-amount-limit.md) | [kotlin]<br>@SerialName(value = &quot;TransactionAmountLimit&quot;)<br>val [transactionAmountLimit](transaction-amount-limit.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Maximum single transaction amount |
| [transactionCountLimit](transaction-count-limit.md) | [kotlin]<br>@SerialName(value = &quot;TransactionCountLimit&quot;)<br>val [transactionCountLimit](transaction-count-limit.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>Maximum number of transactions |
