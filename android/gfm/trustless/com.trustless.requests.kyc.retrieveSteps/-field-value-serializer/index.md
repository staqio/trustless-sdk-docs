//[trustless](../../../index.md)/[com.trustless.requests.kyc.retrieveSteps](../index.md)/[FieldValueSerializer](index.md)

# FieldValueSerializer

[kotlin]\
class [FieldValueSerializer](index.md) : KSerializer&lt;[FieldValue](../-field-value/index.md)&gt;

## Constructors

| | |
|---|---|
| [FieldValueSerializer](-field-value-serializer.md) | [kotlin]<br>constructor() |

## Properties

| Name | Summary |
|---|---|
| [descriptor](descriptor.md) | [kotlin]<br>open override val [descriptor](descriptor.md): SerialDescriptor |

## Functions

| Name | Summary |
|---|---|
| [deserialize](deserialize.md) | [kotlin]<br>open override fun [deserialize](deserialize.md)(decoder: Decoder): [FieldValue](../-field-value/index.md) |
| [serialize](serialize.md) | [kotlin]<br>open override fun [serialize](serialize.md)(encoder: Encoder, obj: [FieldValue](../-field-value/index.md)) |
