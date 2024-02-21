//[trustless](../../../index.md)/[com.trustless.requests.cards.topUp](../index.md)/[ChangeCardBalanceParams](index.md)

# ChangeCardBalanceParams

class [ChangeCardBalanceParams](index.md)constructor(accountNumber: String, amount: Double, currency: String) : [JSONParamsBuilder](../../com.trustless.params/-j-s-o-n-params-builder/index.md)

Top up card params

#### Parameters

kotlin

| | |
|---|---|
| accountNumber | Bank Account number to be used as a source of funds for the card. The account should have a sufficient balance |
| amount | Amount to be credited to the card MAXIMUM: 1000000000000000000 MINIMUM: 0.0001 |
| currency | ISO 3 chars currency code (e.g. &quot;JOD&quot;, &quot;USD&quot;, &quot;EUR&quot;) PATTERN: ^A-Z{3}$ |

#### Throws

| |
|---|
| [TrustlessCurrencyCodeException](../../com.trustless.exceptions/-trustless-currency-code-exception/index.md) |
| [TrustlessAmountException](../../com.trustless.exceptions/-trustless-amount-exception/index.md) |

## Constructors

| | |
|---|---|
| [ChangeCardBalanceParams](-change-card-balance-params.md) | [kotlin]<br>constructor(accountNumber: String, amount: Double, currency: String) |
