//[trustless](../../index.md)/[com.trustless.validators](index.md)/[validateMonth](validate-month.md)

# validateMonth

[kotlin]\
fun [validateMonth](validate-month.md)(month: Int)

Throws a TrustlessMonthException if the provided month integer is not valid. This function utilizes isMonthValid to check the month's validity and acts as a guard in contexts where an invalid month value cannot be tolerated.

#### Throws

| | |
|---|---|
| [TrustlessMonthException](../com.trustless.exceptions/-trustless-month-exception/index.md) | if month is invalid |
