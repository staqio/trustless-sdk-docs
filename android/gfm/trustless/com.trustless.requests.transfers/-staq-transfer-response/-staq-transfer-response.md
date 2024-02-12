//[trustless](../../../index.md)/[com.trustless.requests.transfers](../index.md)/[StaqTransferResponse](index.md)/[StaqTransferResponse](-staq-transfer-response.md)

# StaqTransferResponse

[kotlin]\
constructor(transferId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), type: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), transferType: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), transferNote: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), timestamp: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, status: [StaqTransferResponseStatus](../-staq-transfer-response-status/index.md), localCurrencyAmount: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), exchangeRate: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), transferCurrency: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), transferAmount: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), chargeType: [StaqTransferResponseChargeType](../-staq-transfer-response-charge-type/index.md), beneficiary: [StaqTransferResponseBeneficiary](../-staq-transfer-response-beneficiary/index.md), fees: [StaqTransferResponseFee](../-staq-transfer-response-fee/index.md), requiredDocumentsRaw: [StagRequiredDocuments](../-stag-required-documents/index.md))

#### Parameters

kotlin

| | |
|---|---|
| transferId | The unique transaction id |
| type | Type of transfer |
| transferType | Transfer type |
| transferNote | Transfer note |
| timestamp | Timestamp indicating when transaction was created |
| status | Status of the transfer object. |
| localCurrencyAmount | Transfer amount in local currency MAXIMUM: 1000000000000000000 MINIMUM: 0.00001 |
| exchangeRate | Exchange Rate |
| transferCurrency | ISO3 Currency code for the card (e.g &quot;JOD&quot;, &quot;USD&quot;, &quot;EUR&quot;) PATTERN: ^A-Z{3}$ |
| transferAmount | Transfer amount MAXIMUM: 1000000000000000000 MINIMUM: 0.00001 |
| chargeType | Charge type object. |
| beneficiary | Beneficiary object. |
| fees | Fee object. |
| requiredDocumentsRaw | Object with required documents |
