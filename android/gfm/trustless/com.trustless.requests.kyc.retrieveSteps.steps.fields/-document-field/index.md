//[trustless](../../../index.md)/[com.trustless.requests.kyc.retrieveSteps.steps.fields](../index.md)/[DocumentField](index.md)

# DocumentField

[]\
class [DocumentField](index.md)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), field: [Field](../../com.trustless.requests.kyc.retrieveSteps/-field/index.md), context: [Page](../../com.trustless.requests.kyc.retrieveSteps.steps/-page/index.md), val parentCode: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) : [BaseField](../-base-field/index.md)

## Constructors

| | |
|---|---|
| [DocumentField](-document-field.md) | []<br>constructor(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), field: [Field](../../com.trustless.requests.kyc.retrieveSteps/-field/index.md), context: [Page](../../com.trustless.requests.kyc.retrieveSteps.steps/-page/index.md), parentCode: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |

## Properties

| Name | Summary |
|---|---|
| [code](../-base-field/code.md) | []<br>open override val [code](../-base-field/code.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [dependentField](../-base-field/dependent-field.md) | []<br>open override val [dependentField](../-base-field/dependent-field.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt; |
| [isFromSDK](../-base-field/is-from-s-d-k.md) | []<br>open override val [isFromSDK](../-base-field/is-from-s-d-k.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isRequired](../-base-field/is-required.md) | []<br>open override val [isRequired](../-base-field/is-required.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isVisible](../-base-field/is-visible.md) | []<br>open override var [isVisible](../-base-field/is-visible.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [labelAr](../-base-field/label-ar.md) | []<br>open override val [labelAr](../-base-field/label-ar.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [labelEn](../-base-field/label-en.md) | []<br>open override val [labelEn](../-base-field/label-en.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [parentCode](parent-code.md) | []<br>val [parentCode](parent-code.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [readOnly](../-base-field/read-only.md) | []<br>open override val [readOnly](../-base-field/read-only.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [requiredWhen](../-base-field/required-when.md) | []<br>open override val [requiredWhen](../-base-field/required-when.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[RequiredWhen](../../com.trustless.requests.kyc.retrieveSteps/-required-when/index.md)&gt; |
| [source](../-base-field/source.md) | []<br>open override val [source](../-base-field/source.md): [InputKYCType](../../com.trustless.requests.kyc.retrieveSteps/-input-k-y-c-type/index.md) |
| [sourceField](../-base-field/source-field.md) | []<br>open override val [sourceField](../-base-field/source-field.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [webViewUrl](../-base-field/web-view-url.md) | []<br>open override val [webViewUrl](../-base-field/web-view-url.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

## Functions

| Name | Summary |
|---|---|
| [addFieldValueToJson](add-field-value-to-json.md) | []<br>open override fun [addFieldValueToJson](add-field-value-to-json.md)(json: [JSONObject](https://developer.android.com/reference/kotlin/org/json/JSONObject.html)) |
| [getValue](get-value.md) | []<br>fun [getValue](get-value.md)(): [File](https://developer.android.com/reference/kotlin/java/io/File.html)? |
| [isValid](is-valid.md) | []<br>open override fun [isValid](is-valid.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [putValue](put-value.md) | []<br>fun [putValue](put-value.md)(value: [File](https://developer.android.com/reference/kotlin/java/io/File.html)) |
| [validate](validate.md) | []<br>open override fun [validate](validate.md)(): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[FieldError](../-field-error/index.md)&gt; |
