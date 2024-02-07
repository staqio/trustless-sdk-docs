//[trustless](../../../index.md)/[com.trustless.requests.transfers](../index.md)/[StaqTransferResponse](index.md)

# StaqTransferResponse

\
@Serializable

data class [StaqTransferResponse](index.md)(val transferId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), val type: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val transferType: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val transferNote: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val timestamp: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, val status: [StaqTransferResponseStatus](../-staq-transfer-response-status/index.md), val localCurrencyAmount: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), val exchangeRate: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), val transferCurrency: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val transferAmount: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), val chargeType: [StaqTransferResponseChargeType](../-staq-transfer-response-charge-type/index.md), val beneficiary: [StaqTransferResponseBeneficiary](../-staq-transfer-response-beneficiary/index.md), val fees: [StaqTransferResponseFee](../-staq-transfer-response-fee/index.md), val requiredDocumentsRaw: [StagRequiredDocuments](../-stag-required-documents/index.md))

## Constructors

| | |
|---|---|
| [StaqTransferResponse](-staq-transfer-response.md) | <br>constructor(transferId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), type: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), transferType: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), transferNote: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), timestamp: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, status: [StaqTransferResponseStatus](../-staq-transfer-response-status/index.md), localCurrencyAmount: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), exchangeRate: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), transferCurrency: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), transferAmount: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), chargeType: [StaqTransferResponseChargeType](../-staq-transfer-response-charge-type/index.md), beneficiary: [StaqTransferResponseBeneficiary](../-staq-transfer-response-beneficiary/index.md), fees: [StaqTransferResponseFee](../-staq-transfer-response-fee/index.md), requiredDocumentsRaw: [StagRequiredDocuments](../-stag-required-documents/index.md)) |

## Properties

| Name | Summary |
|---|---|
| [beneficiary](beneficiary.md) | <br>@SerialName(value = &quot;Beneficiary&quot;)<br>val [beneficiary](beneficiary.md): [StaqTransferResponseBeneficiary](../-staq-transfer-response-beneficiary/index.md) |
| [chargeType](charge-type.md) | <br>@SerialName(value = &quot;ChargeType&quot;)<br>val [chargeType](charge-type.md): [StaqTransferResponseChargeType](../-staq-transfer-response-charge-type/index.md) |
| [exchangeRate](exchange-rate.md) | <br>@SerialName(value = &quot;ExchangeRate&quot;)<br>val [exchangeRate](exchange-rate.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [fees](fees.md) | <br>@SerialName(value = &quot;Fees&quot;)<br>val [fees](fees.md): [StaqTransferResponseFee](../-staq-transfer-response-fee/index.md) |
| [localCurrencyAmount](local-currency-amount.md) | <br>@SerialName(value = &quot;LocalCurrencyAmount&quot;)<br>val [localCurrencyAmount](local-currency-amount.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [requiredDocuments](required-documents.md) | <br>val [requiredDocuments](required-documents.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[StagRequiredDocument](../-stag-required-document/index.md)&gt; |
| [requiredDocumentsRaw](required-documents-raw.md) | <br>@SerialName(value = &quot;RequiredDocuments&quot;)<br>val [requiredDocumentsRaw](required-documents-raw.md): [StagRequiredDocuments](../-stag-required-documents/index.md) |
| [status](status.md) | <br>@SerialName(value = &quot;Status&quot;)<br>val [status](status.md): [StaqTransferResponseStatus](../-staq-transfer-response-status/index.md) |
| [timestamp](timestamp.md) | <br>@SerialName(value = &quot;Timestamp&quot;)<br>val [timestamp](timestamp.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [transferAmount](transfer-amount.md) | <br>@SerialName(value = &quot;TransferAmount&quot;)<br>val [transferAmount](transfer-amount.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [transferCurrency](transfer-currency.md) | <br>@SerialName(value = &quot;TransferCurrency&quot;)<br>val [transferCurrency](transfer-currency.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [transferId](transfer-id.md) | <br>@SerialName(value = &quot;TransferId&quot;)<br>val [transferId](transfer-id.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [transferNote](transfer-note.md) | <br>@SerialName(value = &quot;TransferNote&quot;)<br>val [transferNote](transfer-note.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [transferType](transfer-type.md) | <br>@SerialName(value = &quot;TransferType&quot;)<br>val [transferType](transfer-type.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [type](type.md) | <br>@SerialName(value = &quot;Type&quot;)<br>val [type](type.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
