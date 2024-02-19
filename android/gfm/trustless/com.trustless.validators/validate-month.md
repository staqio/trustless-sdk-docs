//[trustless](../../index.md)/[com.trustless.validators](index.md)/[validateMonth](validate-month.md)

# validateMonth

[kotlin]\
fun [validateMonth](validate-month.md)(month: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))

Throws a TrustlessMonthException if the provided month integer is not valid. This function utilizes isMonthValid to check the month's validity and acts as a guard in contexts where an invalid month value cannot be tolerated.
