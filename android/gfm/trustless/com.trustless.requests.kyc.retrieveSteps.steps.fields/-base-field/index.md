//[trustless](../../../index.md)/[com.trustless.requests.kyc.retrieveSteps.steps.fields](../index.md)/[BaseField](index.md)

# BaseField

abstract class [BaseField](index.md)(keyCode: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), field: [Field](../../com.trustless.requests.kyc.retrieveSteps/-field/index.md)) : [FieldManager](../../com.trustless.requests.kyc.retrieveSteps.steps.wrapper/-field-manager/index.md)

#### Inheritors

| |
|---|
| [BooleanField](../-boolean-field/index.md) |
| [DateField](../-date-field/index.md) |
| [DocumentField](../-document-field/index.md) |
| [IntegerField](../-integer-field/index.md) |
| [ListOfValuesField](../-list-of-values-field/index.md) |
| [ProofDocumentField](../-proof-document-field/index.md) |
| [TextField](../-text-field/index.md) |

## Constructors

| | |
|---|---|
| [BaseField](-base-field.md) | []<br>constructor(keyCode: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), field: [Field](../../com.trustless.requests.kyc.retrieveSteps/-field/index.md)) |

## Properties

| Name | Summary |
|---|---|
| [code](code.md) | []<br>open override val [code](code.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [dependentField](dependent-field.md) | []<br>open override val [dependentField](dependent-field.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt; |
| [isFromSDK](is-from-s-d-k.md) | []<br>open override val [isFromSDK](is-from-s-d-k.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isRequired](is-required.md) | []<br>open override val [isRequired](is-required.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isVisible](is-visible.md) | []<br>open override var [isVisible](is-visible.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [labelAr](label-ar.md) | []<br>open override val [labelAr](label-ar.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [labelEn](label-en.md) | []<br>open override val [labelEn](label-en.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [readOnly](read-only.md) | []<br>open override val [readOnly](read-only.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [requiredWhen](required-when.md) | []<br>open override val [requiredWhen](required-when.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[RequiredWhen](../../com.trustless.requests.kyc.retrieveSteps/-required-when/index.md)&gt; |
| [source](source.md) | []<br>open override val [source](source.md): [InputKYCType](../../com.trustless.requests.kyc.retrieveSteps/-input-k-y-c-type/index.md) |
| [sourceField](source-field.md) | []<br>open override val [sourceField](source-field.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [webViewUrl](web-view-url.md) | []<br>open override val [webViewUrl](web-view-url.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

## Functions

| Name | Summary |
|---|---|
| [addFieldValueToJson](../../com.trustless.requests.kyc.retrieveSteps.steps.wrapper/-field-manager/add-field-value-to-json.md) | []<br>abstract fun [addFieldValueToJson](../../com.trustless.requests.kyc.retrieveSteps.steps.wrapper/-field-manager/add-field-value-to-json.md)(json: [JSONObject](https://developer.android.com/reference/kotlin/org/json/JSONObject.html)) |
| [isValid](../../com.trustless.requests.kyc.retrieveSteps.steps.wrapper/-field-manager/is-valid.md) | []<br>abstract fun [isValid](../../com.trustless.requests.kyc.retrieveSteps.steps.wrapper/-field-manager/is-valid.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [validate](../../com.trustless.requests.kyc.retrieveSteps.steps.wrapper/-field-manager/validate.md) | []<br>abstract fun [validate](../../com.trustless.requests.kyc.retrieveSteps.steps.wrapper/-field-manager/validate.md)(): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[FieldError](../-field-error/index.md)&gt; |
