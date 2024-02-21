//[trustless](../../../index.md)/[com.trustless.requests.cards.setLimits](../index.md)/[SetLimitsParams](index.md)/[SetLimitsParams](-set-limits-params.md)

# SetLimitsParams

[kotlin]\
constructor(period: String, cashLimit: Double?, eCommerceLimit: Double?)

#### Parameters

kotlin

| | |
|---|---|
| period | Limit period DEFAULT: daily ENUM:  daily, weekly, monthly, annually |
| cashLimit | ATM operations limit amount If it is set to 0 (zero) then no ATM operations are allowed for the card. If it is set to < 0 (negative value) then card ATM limit is disabled and card product limit (if any) is applied. MAXIMUM: 1000000000000 |
| eCommerceLimit | E-commerce (Online authorizations) limit amount If it is set to 0 (zero) then no ATM operations are allowed for the card. If it is set to < 0 (negative value) then E-commerce card is disabled and card product limit (if any) is applied. MAXIMUM: 1000000000000 |
