//[trustless](../../../index.md)/[com.trustless.requests.transfers](../index.md)/[CreateCliqTransferParams](index.md)/[CreateCliqTransferParams](-create-cliq-transfer-params.md)

# CreateCliqTransferParams

[kotlin]\
constructor(accountNumber: String, beneficiaryAliasType: String, beneficiaryAlias: String, amount: Double, currencyCode: String, purposeCode: String, transferNote: String? = null)

#### Parameters

kotlin

| | |
|---|---|
| accountNumber | Customer Account Number |
| beneficiaryAliasType | Beneficiary Alias Type ENUM:  ALIAS, MOBL |
| beneficiaryAlias | Beneficiary Alias |
| amount | Transfer amount MAXIMUM: 1000000000000000000 MINIMUM: 0.00001 |
| currencyCode | ISO3 Currency code for the card (e.g &quot;JOD&quot;, &quot;USD&quot;, &quot;EUR&quot;) PATTERN: ^A-Z{3}$ |
| transferNote | Transfer note |
