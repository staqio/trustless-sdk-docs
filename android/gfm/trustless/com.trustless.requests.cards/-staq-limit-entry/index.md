//[trustless](../../../index.md)/[com.trustless.requests.cards](../index.md)/[StaqLimitEntry](index.md)

# StaqLimitEntry

[kotlin]\
@Serializable

data class [StaqLimitEntry](index.md)

Limit entry

## Properties

| Name | Summary |
|---|---|
| [limit](limit.md) | [kotlin]<br>@SerialName(value = &quot;Limit&quot;)<br>val [limit](limit.md): Double<br>Maximum limit amount |
| [remainingAmount](remaining-amount.md) | [kotlin]<br>@SerialName(value = &quot;RemainingAmount&quot;)<br>val [remainingAmount](remaining-amount.md): Double? = null<br>Remaining Amount Limit |
| [remainingCount](remaining-count.md) | [kotlin]<br>@SerialName(value = &quot;RemainingCount&quot;)<br>val [remainingCount](remaining-count.md): Int? = null<br>Remainig Count Limit |
| [transactionAmountLimit](transaction-amount-limit.md) | [kotlin]<br>@SerialName(value = &quot;TransactionAmountLimit&quot;)<br>val [transactionAmountLimit](transaction-amount-limit.md): Double<br>Maximum single transaction amount |
| [transactionCountLimit](transaction-count-limit.md) | [kotlin]<br>@SerialName(value = &quot;TransactionCountLimit&quot;)<br>val [transactionCountLimit](transaction-count-limit.md): Int<br>Maximum number of transactions |
