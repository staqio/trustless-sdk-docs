//[trustless](../../../index.md)/[com.trustless.requests.transfers](../index.md)/[StaqTransferResponseChargeType](index.md)

# StaqTransferResponseChargeType

[kotlin]\
@Serializable

data class [StaqTransferResponseChargeType](index.md)(val chargeTypeId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), val chargeTypeCode: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val chargeTypeName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))

Charge type object

## Constructors

| | |
|---|---|
| [StaqTransferResponseChargeType](-staq-transfer-response-charge-type.md) | [kotlin]<br>constructor(chargeTypeId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), chargeTypeCode: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), chargeTypeName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |

## Properties

| Name | Summary |
|---|---|
| [chargeTypeCode](charge-type-code.md) | [kotlin]<br>@SerialName(value = &quot;ChargeTypeCode&quot;)<br>val [chargeTypeCode](charge-type-code.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>Charge Type Code |
| [chargeTypeId](charge-type-id.md) | [kotlin]<br>@SerialName(value = &quot;ChargeTypeId&quot;)<br>val [chargeTypeId](charge-type-id.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>The unique charge type id |
| [chargeTypeName](charge-type-name.md) | [kotlin]<br>@SerialName(value = &quot;ChargeTypeName&quot;)<br>val [chargeTypeName](charge-type-name.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>Charge Type Name |
