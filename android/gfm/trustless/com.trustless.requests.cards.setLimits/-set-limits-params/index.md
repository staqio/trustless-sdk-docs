//[trustless](../../../index.md)/[com.trustless.requests.cards.setLimits](../index.md)/[SetLimitsParams](index.md)

# SetLimitsParams

class [SetLimitsParams](index.md)(period: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), cashLimit: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)?, eCommerceLimit: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)?) : [JSONParamsBuilder](../../com.trustless.params/-j-s-o-n-params-builder/index.md)

Set limit params

[Server Api Reference](https://developer.staq.io/docs/apis/cards#/Limits/Set%20a%20card%20spending%20limits)

#### Parameters

kotlin

| | |
|---|---|
| period | Limit period DEFAULT: daily ENUM:  daily, weekly, monthly, annually |
| cashLimit | ATM operations limit amount If it is set to 0 (zero) then no ATM operations are allowed for the card. If it is set to < 0 (negative value) then card ATM limit is disabled and card product limit (if any) is applied. MAXIMUM: 1000000000000 |
| eCommerceLimit | E-commerce (Online authorizations) limit amount If it is set to 0 (zero) then no ATM operations are allowed for the card. If it is set to < 0 (negative value) then E-commerce card is disabled and card product limit (if any) is applied. MAXIMUM: 1000000000000 |

#### Throws

| |
|---|
| [TrustlessLimitException](../../com.trustless.exceptions/-trustless-limit-exception/index.md) |

## Constructors

| | |
|---|---|
| [SetLimitsParams](-set-limits-params.md) | [kotlin]<br>constructor(period: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), cashLimit: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)?, eCommerceLimit: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)?) |
