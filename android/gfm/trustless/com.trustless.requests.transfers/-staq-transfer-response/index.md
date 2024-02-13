//[trustless](../../../index.md)/[com.trustless.requests.transfers](../index.md)/[StaqTransferResponse](index.md)

# StaqTransferResponse

[kotlin]\
@Serializable

data class [StaqTransferResponse](index.md)(val transferId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), val type: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val transferType: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val transferNote: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val timestamp: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, val status: [StaqTransferResponseStatus](../-staq-transfer-response-status/index.md), val localCurrencyAmount: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), val exchangeRate: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), val transferCurrency: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val transferAmount: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), val chargeType: [StaqTransferResponseChargeType](../-staq-transfer-response-charge-type/index.md), val beneficiary: [StaqTransferResponseBeneficiary](../-staq-transfer-response-beneficiary/index.md), val fees: [StaqTransferResponseFee](../-staq-transfer-response-fee/index.md), val requiredDocumentsRaw: [StagRequiredDocuments](../-stag-required-documents/index.md))

Transfer object.

## Constructors

| | |
|---|---|
| [StaqTransferResponse](-staq-transfer-response.md) | [kotlin]<br>constructor(transferId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), type: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), transferType: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), transferNote: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), timestamp: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, status: [StaqTransferResponseStatus](../-staq-transfer-response-status/index.md), localCurrencyAmount: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), exchangeRate: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), transferCurrency: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), transferAmount: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), chargeType: [StaqTransferResponseChargeType](../-staq-transfer-response-charge-type/index.md), beneficiary: [StaqTransferResponseBeneficiary](../-staq-transfer-response-beneficiary/index.md), fees: [StaqTransferResponseFee](../-staq-transfer-response-fee/index.md), requiredDocumentsRaw: [StagRequiredDocuments](../-stag-required-documents/index.md)) |

## Properties

| Name | Summary |
|---|---|
| [beneficiary](beneficiary.md) | [kotlin]<br>@SerialName(value = &quot;Beneficiary&quot;)<br>val [beneficiary](beneficiary.md): [StaqTransferResponseBeneficiary](../-staq-transfer-response-beneficiary/index.md)<br>Beneficiary object. |
| [chargeType](charge-type.md) | [kotlin]<br>@SerialName(value = &quot;ChargeType&quot;)<br>val [chargeType](charge-type.md): [StaqTransferResponseChargeType](../-staq-transfer-response-charge-type/index.md)<br>Charge type object. |
| [exchangeRate](exchange-rate.md) | [kotlin]<br>@SerialName(value = &quot;ExchangeRate&quot;)<br>val [exchangeRate](exchange-rate.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>Exchange Rate |
| [fees](fees.md) | [kotlin]<br>@SerialName(value = &quot;Fees&quot;)<br>val [fees](fees.md): [StaqTransferResponseFee](../-staq-transfer-response-fee/index.md)<br>Fee object. |
| [localCurrencyAmount](local-currency-amount.md) | [kotlin]<br>@SerialName(value = &quot;LocalCurrencyAmount&quot;)<br>val [localCurrencyAmount](local-currency-amount.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Transfer amount in local currency MAXIMUM: 1000000000000000000 MINIMUM: 0.00001 |
| [requiredDocuments](required-documents.md) | [kotlin]<br>val [requiredDocuments](required-documents.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[StagRequiredDocument](../-stag-required-document/index.md)&gt;<br>Required documents array, that fixes weird structure that is coming from the server. |
| [requiredDocumentsRaw](required-documents-raw.md) | [kotlin]<br>@SerialName(value = &quot;RequiredDocuments&quot;)<br>val [requiredDocumentsRaw](required-documents-raw.md): [StagRequiredDocuments](../-stag-required-documents/index.md)<br>Object with required documents |
| [status](status.md) | [kotlin]<br>@SerialName(value = &quot;Status&quot;)<br>val [status](status.md): [StaqTransferResponseStatus](../-staq-transfer-response-status/index.md)<br>Status of the transfer object. |
| [timestamp](timestamp.md) | [kotlin]<br>@SerialName(value = &quot;Timestamp&quot;)<br>val [timestamp](timestamp.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null<br>Timestamp indicating when transaction was created |
| [transferAmount](transfer-amount.md) | [kotlin]<br>@SerialName(value = &quot;TransferAmount&quot;)<br>val [transferAmount](transfer-amount.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Transfer amount MAXIMUM: 1000000000000000000 MINIMUM: 0.00001 |
| [transferCurrency](transfer-currency.md) | [kotlin]<br>@SerialName(value = &quot;TransferCurrency&quot;)<br>val [transferCurrency](transfer-currency.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>ISO3 Currency code for the card (e.g &quot;JOD&quot;, &quot;USD&quot;, &quot;EUR&quot;) PATTERN: ^A-Z{3}$ |
| [transferId](transfer-id.md) | [kotlin]<br>@SerialName(value = &quot;TransferId&quot;)<br>val [transferId](transfer-id.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>The unique transaction id |
| [transferNote](transfer-note.md) | [kotlin]<br>@SerialName(value = &quot;TransferNote&quot;)<br>val [transferNote](transfer-note.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>Transfer note |
| [transferType](transfer-type.md) | [kotlin]<br>@SerialName(value = &quot;TransferType&quot;)<br>val [transferType](transfer-type.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>Transfer type |
| [type](type.md) | [kotlin]<br>@SerialName(value = &quot;Type&quot;)<br>val [type](type.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>Type of transfer |
