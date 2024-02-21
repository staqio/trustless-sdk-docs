//[trustless](../../../index.md)/[com.trustless.requests.kyc.retrieveSteps.steps.fields](../index.md)/[DateField](index.md)

# DateField

[kotlin]\
class [DateField](index.md) : [BaseField](../-base-field/index.md)

## Properties

| Name | Summary |
|---|---|
| [code](../-base-field/code.md) | [kotlin]<br>open override val [code](../-base-field/code.md): String<br>a code for the field, primarily used internally |
| [dependentField](../-base-field/dependent-field.md) | [kotlin]<br>open override val [dependentField](../-base-field/dependent-field.md): List&lt;String&gt;<br>a list of fields that this field is depended on |
| [isFromSDK](../-base-field/is-from-s-d-k.md) | [kotlin]<br>open override val [isFromSDK](../-base-field/is-from-s-d-k.md): Boolean<br>is the source type of the filed is SDK |
| [isRequired](../-base-field/is-required.md) | [kotlin]<br>open override val [isRequired](../-base-field/is-required.md): Boolean<br>if the field is required to fill in |
| [isVisible](../-base-field/is-visible.md) | [kotlin]<br>open override var [isVisible](../-base-field/is-visible.md): Boolean<br>if the field should be visible, with the current other fields values. For example, if user answers a field with a question &quot;Are you a student?&quot;: &quot;No&quot;, the other field's property isVisible with the question &quot;What year are you?&quot;, will be automatically set to false. |
| [labelAr](../-base-field/label-ar.md) | [kotlin]<br>open override val [labelAr](../-base-field/label-ar.md): String<br>Arabic label for a field |
| [labelEn](../-base-field/label-en.md) | [kotlin]<br>open override val [labelEn](../-base-field/label-en.md): String<br>English label for a field |
| [readOnly](../-base-field/read-only.md) | [kotlin]<br>open override val [readOnly](../-base-field/read-only.md): Boolean<br>if a field read only |
| [source](../-base-field/source.md) | [kotlin]<br>open override val [source](../-base-field/source.md): [InputKYCType](../../com.trustless.requests.kyc.retrieveSteps/-input-k-y-c-type/index.md)<br>the source of data for the field, could be: USER, INPUT, UNKNOWN, SDK, DOCUMENT |
| [sourceField](../-base-field/source-field.md) | [kotlin]<br>open override val [sourceField](../-base-field/source-field.md): String<br>A key for sourceFields object to get the data from |
| [webViewUrl](../-base-field/web-view-url.md) | [kotlin]<br>open override val [webViewUrl](../-base-field/web-view-url.md): String<br>url that should be opened in the webview |

## Functions

| Name | Summary |
|---|---|
| [getValue](get-value.md) | [kotlin]<br>fun [getValue](get-value.md)(): String<br>returns field value |
| [isValid](is-valid.md) | [kotlin]<br>open override fun [isValid](is-valid.md)(): Boolean<br>if the current field has valid data |
| [putValue](put-value.md) | [kotlin]<br>fun [putValue](put-value.md)(value: String)<br>Put value to field in format dd-mm-yyyy |
| [validate](validate.md) | [kotlin]<br>open override fun [validate](validate.md)(): List&lt;[FieldError](../-field-error/index.md)&gt;<br>returns a list with errors, empty array if the field is valid |
