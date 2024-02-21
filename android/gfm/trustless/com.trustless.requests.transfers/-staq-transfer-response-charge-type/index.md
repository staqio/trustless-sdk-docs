//[trustless](../../../index.md)/[com.trustless.requests.transfers](../index.md)/[StaqTransferResponseChargeType](index.md)

# StaqTransferResponseChargeType

[kotlin]\
@Serializable

data class [StaqTransferResponseChargeType](index.md)(val chargeTypeId: Int, val chargeTypeCode: String, val chargeTypeName: String)

Charge type object

## Constructors

| | |
|---|---|
| [StaqTransferResponseChargeType](-staq-transfer-response-charge-type.md) | [kotlin]<br>constructor(chargeTypeId: Int, chargeTypeCode: String, chargeTypeName: String) |

## Properties

| Name | Summary |
|---|---|
| [chargeTypeCode](charge-type-code.md) | [kotlin]<br>@SerialName(value = &quot;ChargeTypeCode&quot;)<br>val [chargeTypeCode](charge-type-code.md): String<br>Charge Type Code |
| [chargeTypeId](charge-type-id.md) | [kotlin]<br>@SerialName(value = &quot;ChargeTypeId&quot;)<br>val [chargeTypeId](charge-type-id.md): Int<br>The unique charge type id |
| [chargeTypeName](charge-type-name.md) | [kotlin]<br>@SerialName(value = &quot;ChargeTypeName&quot;)<br>val [chargeTypeName](charge-type-name.md): String<br>Charge Type Name |
