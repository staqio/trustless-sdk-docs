//[trustless](../../index.md)/[com.trustless.requests.kyc.retrieveSteps](index.md)

# Package-level declarations

## Types

| Name | Summary |
|---|---|
| [FieldValue](-field-value/index.md) | [kotlin]<br>@Serializable(with = FieldValueSerializer::class)<br>abstract class [FieldValue](-field-value/index.md) |
| [InputKYCType](-input-k-y-c-type/index.md) | [kotlin]<br>enum [InputKYCType](-input-k-y-c-type/index.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)&lt;[InputKYCType](-input-k-y-c-type/index.md)&gt; <br>KYC (Know your customer) field types |
| [RequiredWhen](-required-when/index.md) | [kotlin]<br>@Serializable<br>data class [RequiredWhen](-required-when/index.md)(val operation: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, val value: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[RequiredWhenValue](-required-when-value/index.md)&gt;) |
| [RequiredWhenValue](-required-when-value/index.md) | [kotlin]<br>@Serializable<br>data class [RequiredWhenValue](-required-when-value/index.md)(val field: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val operation: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val value: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[FieldValue](-field-value/index.md)&gt;? = null) |
