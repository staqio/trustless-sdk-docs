//[trustless](../../../index.md)/[com.trustless.requests.cards.topUp](../index.md)/[ChangeCardBalanceParams](index.md)/[ChangeCardBalanceParams](-change-card-balance-params.md)

# ChangeCardBalanceParams

[kotlin]\
constructor(accountNumber: String, amount: Double, currency: String)

#### Parameters

kotlin

| | |
|---|---|
| accountNumber | Bank Account number to be used as a source of funds for the card. The account should have a sufficient balance |
| amount | Amount to be credited to the card MAXIMUM: 1000000000000000000 MINIMUM: 0.0001 |
| currency | ISO 3 chars currency code (e.g. &quot;JOD&quot;, &quot;USD&quot;, &quot;EUR&quot;) PATTERN: ^A-Z{3}$ |
