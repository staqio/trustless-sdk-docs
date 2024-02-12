//[trustless](../../../index.md)/[com.trustless.requests.kyc.retrieveSteps.steps.wrapper](../index.md)/[FieldManager](index.md)

# FieldManager

interface [FieldManager](index.md)

#### Inheritors

| |
|---|
| [BaseField](../../com.trustless.requests.kyc.retrieveSteps.steps.fields/-base-field/index.md) |

## Properties

| Name | Summary |
|---|---|
| [code](code.md) | [kotlin]<br>abstract val [code](code.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [dependentField](dependent-field.md) | [kotlin]<br>abstract val [dependentField](dependent-field.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt; |
| [isFromSDK](is-from-s-d-k.md) | [kotlin]<br>abstract val [isFromSDK](is-from-s-d-k.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isRequired](is-required.md) | [kotlin]<br>abstract val [isRequired](is-required.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isVisible](is-visible.md) | [kotlin]<br>abstract var [isVisible](is-visible.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [labelAr](label-ar.md) | [kotlin]<br>abstract val [labelAr](label-ar.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [labelEn](label-en.md) | [kotlin]<br>abstract val [labelEn](label-en.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [readOnly](read-only.md) | [kotlin]<br>abstract val [readOnly](read-only.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [requiredWhen](required-when.md) | [kotlin]<br>abstract val [requiredWhen](required-when.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[RequiredWhen](../../com.trustless.requests.kyc.retrieveSteps/-required-when/index.md)&gt; |
| [source](source.md) | [kotlin]<br>abstract val [source](source.md): [InputKYCType](../../com.trustless.requests.kyc.retrieveSteps/-input-k-y-c-type/index.md) |
| [sourceField](source-field.md) | [kotlin]<br>abstract val [sourceField](source-field.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [webViewUrl](web-view-url.md) | [kotlin]<br>abstract val [webViewUrl](web-view-url.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

## Functions

| Name | Summary |
|---|---|
| [addFieldValueToJson](add-field-value-to-json.md) | [kotlin]<br>abstract fun [addFieldValueToJson](add-field-value-to-json.md)(json: [JSONObject](https://developer.android.com/reference/kotlin/org/json/JSONObject.html)) |
| [isValid](is-valid.md) | [kotlin]<br>abstract fun [isValid](is-valid.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [validate](validate.md) | [kotlin]<br>abstract fun [validate](validate.md)(): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[FieldError](../../com.trustless.requests.kyc.retrieveSteps.steps.fields/-field-error/index.md)&gt; |