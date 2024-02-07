//[trustless](../../../index.md)/[com.trustless.requests.kyc.retrieveSteps.steps.fields](../index.md)/[UrlField](index.md)

# UrlField

[kotlin]\
class [UrlField](index.md)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), field: [Field](../../com.trustless.requests.kyc.retrieveSteps/-field/index.md), context: [Page](../../com.trustless.requests.kyc.retrieveSteps.steps/-page/index.md)) : [ListOfValuesField](../-list-of-values-field/index.md)

## Constructors

| | |
|---|---|
| [UrlField](-url-field.md) | [kotlin]<br>constructor(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), field: [Field](../../com.trustless.requests.kyc.retrieveSteps/-field/index.md), context: [Page](../../com.trustless.requests.kyc.retrieveSteps.steps/-page/index.md)) |

## Properties

| Name | Summary |
|---|---|
| [code](../-base-field/code.md) | [kotlin]<br>open override val [code](../-base-field/code.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [dependentField](../-base-field/dependent-field.md) | [kotlin]<br>open override val [dependentField](../-base-field/dependent-field.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt; |
| [isFromSDK](../-base-field/is-from-s-d-k.md) | [kotlin]<br>open override val [isFromSDK](../-base-field/is-from-s-d-k.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isRequired](../-base-field/is-required.md) | [kotlin]<br>open override val [isRequired](../-base-field/is-required.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isVisible](../-base-field/is-visible.md) | [kotlin]<br>open override var [isVisible](../-base-field/is-visible.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [labelAr](../-base-field/label-ar.md) | [kotlin]<br>open override val [labelAr](../-base-field/label-ar.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [labelEn](../-base-field/label-en.md) | [kotlin]<br>open override val [labelEn](../-base-field/label-en.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [readOnly](../-base-field/read-only.md) | [kotlin]<br>open override val [readOnly](../-base-field/read-only.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [requiredWhen](../-base-field/required-when.md) | [kotlin]<br>open override val [requiredWhen](../-base-field/required-when.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[RequiredWhen](../../com.trustless.requests.kyc.retrieveSteps/-required-when/index.md)&gt; |
| [source](../-base-field/source.md) | [kotlin]<br>open override val [source](../-base-field/source.md): [InputKYCType](../../com.trustless.requests.kyc.retrieveSteps/-input-k-y-c-type/index.md) |
| [sourceField](../-base-field/source-field.md) | [kotlin]<br>open override val [sourceField](../-base-field/source-field.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [webViewUrl](../-base-field/web-view-url.md) | [kotlin]<br>open override val [webViewUrl](../-base-field/web-view-url.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

## Functions

| Name | Summary |
|---|---|
| [addFieldValueToJson](../-list-of-values-field/add-field-value-to-json.md) | [kotlin]<br>open override fun [addFieldValueToJson](../-list-of-values-field/add-field-value-to-json.md)(json: [JSONObject](https://developer.android.com/reference/kotlin/org/json/JSONObject.html)) |
| [getChoicesAr](get-choices-ar.md) | [kotlin]<br>open override fun [getChoicesAr](get-choices-ar.md)(): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt; |
| [getChoicesEn](get-choices-en.md) | [kotlin]<br>open override fun [getChoicesEn](get-choices-en.md)(): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt; |
| [getCurrentValueAr](../-list-of-values-field/get-current-value-ar.md) | [kotlin]<br>fun [getCurrentValueAr](../-list-of-values-field/get-current-value-ar.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [getCurrentValueEn](../-list-of-values-field/get-current-value-en.md) | [kotlin]<br>fun [getCurrentValueEn](../-list-of-values-field/get-current-value-en.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [getValue](../-list-of-values-field/get-value.md) | [kotlin]<br>fun [getValue](../-list-of-values-field/get-value.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [getValueFromDependentField](get-value-from-dependent-field.md) | [kotlin]<br>fun [getValueFromDependentField](get-value-from-dependent-field.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? |
| [hasDependentFieldChanged](has-dependent-field-changed.md) | [kotlin]<br>fun [hasDependentFieldChanged](has-dependent-field-changed.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isValid](../-list-of-values-field/is-valid.md) | [kotlin]<br>open override fun [isValid](../-list-of-values-field/is-valid.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [putValue](../-list-of-values-field/put-value.md) | [kotlin]<br>fun [putValue](../-list-of-values-field/put-value.md)(value: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |
| [setChoices](set-choices.md) | [kotlin]<br>fun [setChoices](set-choices.md)(choicesEn: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt;, choicesAr: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt;) |
| [validate](../-list-of-values-field/validate.md) | [kotlin]<br>open override fun [validate](../-list-of-values-field/validate.md)(): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[FieldError](../-field-error/index.md)&gt; |
