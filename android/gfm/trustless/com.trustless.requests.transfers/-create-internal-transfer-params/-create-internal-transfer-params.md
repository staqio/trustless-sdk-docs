//[trustless](../../../index.md)/[com.trustless.requests.transfers](../index.md)/[CreateInternalTransferParams](index.md)/[CreateInternalTransferParams](-create-internal-transfer-params.md)

# CreateInternalTransferParams

[kotlin]\
constructor(accountNumber: String, beneficiaryAccount: String, amount: Double, currencyCode: String, transferNote: String? = null)

#### Parameters

kotlin

| | |
|---|---|
| accountNumber | Customer Account Number |
| beneficiaryAccount | Beneficiary Account Number |
| amount | Transfer amount MAXIMUM: 1000000000000000000 MINIMUM: 0.00001 |
| currencyCode | ISO3 Currency code for the card (e.g &quot;JOD&quot;, &quot;USD&quot;, &quot;EUR&quot;) PATTERN: ^A-Z{3}$ |
| transferNote | Transfer note |
