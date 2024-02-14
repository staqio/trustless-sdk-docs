//[trustless](../../../index.md)/[com.trustless.requests.kyc.retrieveSteps.steps.fields](../index.md)/[IntegerField](index.md)

# IntegerField

[kotlin]\
class [IntegerField](index.md) : [BaseField](../-base-field/index.md)

## Properties

| Name | Summary |
|---|---|
| [code](../-base-field/code.md) | [kotlin]<br>open override val [code](../-base-field/code.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>a code for the field, primarily used internally |
| [dependentField](../-base-field/dependent-field.md) | [kotlin]<br>open override val [dependentField](../-base-field/dependent-field.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt;<br>a list of fields that this field is depended on |
| [isFromSDK](../-base-field/is-from-s-d-k.md) | [kotlin]<br>open override val [isFromSDK](../-base-field/is-from-s-d-k.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>is the source type of the filed is SDK |
| [isRequired](../-base-field/is-required.md) | [kotlin]<br>open override val [isRequired](../-base-field/is-required.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>if the field is required to fill in |
| [isVisible](../-base-field/is-visible.md) | [kotlin]<br>open override var [isVisible](../-base-field/is-visible.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>if the field should be visible, with the current other fields values. For example, if user answers a field with a question &quot;Are you a student?&quot;: &quot;No&quot;, the other field's property isVisible with the question &quot;What year are you?&quot;, will be automatically set to false. |
| [labelAr](../-base-field/label-ar.md) | [kotlin]<br>open override val [labelAr](../-base-field/label-ar.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>Arabic label for a field |
| [labelEn](../-base-field/label-en.md) | [kotlin]<br>open override val [labelEn](../-base-field/label-en.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>English label for a field |
| [readOnly](../-base-field/read-only.md) | [kotlin]<br>open override val [readOnly](../-base-field/read-only.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>if a field read only |
| [source](../-base-field/source.md) | [kotlin]<br>open override val [source](../-base-field/source.md): [InputKYCType](../../com.trustless.requests.kyc.retrieveSteps/-input-k-y-c-type/index.md)<br>the source of data for the field, could be: USER, INPUT, UNKNOWN, SDK, DOCUMENT |
| [sourceField](../-base-field/source-field.md) | [kotlin]<br>open override val [sourceField](../-base-field/source-field.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>A key for sourceFields object to get the data from |
| [webViewUrl](../-base-field/web-view-url.md) | [kotlin]<br>open override val [webViewUrl](../-base-field/web-view-url.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>url that should be opened in the webview |

## Functions

| Name | Summary |
|---|---|
| [getValue](get-value.md) | [kotlin]<br>fun [getValue](get-value.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>Gets String value or &quot;&quot; |
| [isValid](is-valid.md) | [kotlin]<br>open override fun [isValid](is-valid.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>if the current field has valid data |
| [putValue](put-value.md) | [kotlin]<br>fun [putValue](put-value.md)(value: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>Puts int value |
| [validate](validate.md) | [kotlin]<br>open override fun [validate](validate.md)(): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[FieldError](../-field-error/index.md)&gt;<br>returns a list with errors, empty array if the field is valid |
