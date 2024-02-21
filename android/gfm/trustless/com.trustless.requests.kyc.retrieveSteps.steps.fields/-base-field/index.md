//[trustless](../../../index.md)/[com.trustless.requests.kyc.retrieveSteps.steps.fields](../index.md)/[BaseField](index.md)

# BaseField

sealed class [BaseField](index.md) : [FieldManager](../../com.trustless.requests.kyc.retrieveSteps.steps.wrapper/-field-manager/index.md)

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

## Properties

| Name | Summary |
|---|---|
| [code](code.md) | [kotlin]<br>open override val [code](code.md): String<br>a code for the field, primarily used internally |
| [dependentField](dependent-field.md) | [kotlin]<br>open override val [dependentField](dependent-field.md): List&lt;String&gt;<br>a list of fields that this field is depended on |
| [isFromSDK](is-from-s-d-k.md) | [kotlin]<br>open override val [isFromSDK](is-from-s-d-k.md): Boolean<br>is the source type of the filed is SDK |
| [isRequired](is-required.md) | [kotlin]<br>open override val [isRequired](is-required.md): Boolean<br>if the field is required to fill in |
| [isVisible](is-visible.md) | [kotlin]<br>open override var [isVisible](is-visible.md): Boolean<br>if the field should be visible, with the current other fields values. For example, if user answers a field with a question &quot;Are you a student?&quot;: &quot;No&quot;, the other field's property isVisible with the question &quot;What year are you?&quot;, will be automatically set to false. |
| [labelAr](label-ar.md) | [kotlin]<br>open override val [labelAr](label-ar.md): String<br>Arabic label for a field |
| [labelEn](label-en.md) | [kotlin]<br>open override val [labelEn](label-en.md): String<br>English label for a field |
| [readOnly](read-only.md) | [kotlin]<br>open override val [readOnly](read-only.md): Boolean<br>if a field read only |
| [source](source.md) | [kotlin]<br>open override val [source](source.md): [InputKYCType](../../com.trustless.requests.kyc.retrieveSteps/-input-k-y-c-type/index.md)<br>the source of data for the field, could be: USER, INPUT, UNKNOWN, SDK, DOCUMENT |
| [sourceField](source-field.md) | [kotlin]<br>open override val [sourceField](source-field.md): String<br>A key for sourceFields object to get the data from |
| [webViewUrl](web-view-url.md) | [kotlin]<br>open override val [webViewUrl](web-view-url.md): String<br>url that should be opened in the webview |

## Functions

| Name | Summary |
|---|---|
| [isValid](../../com.trustless.requests.kyc.retrieveSteps.steps.wrapper/-field-manager/is-valid.md) | [kotlin]<br>abstract fun [isValid](../../com.trustless.requests.kyc.retrieveSteps.steps.wrapper/-field-manager/is-valid.md)(): Boolean<br>if the current field has valid data |
| [validate](../../com.trustless.requests.kyc.retrieveSteps.steps.wrapper/-field-manager/validate.md) | [kotlin]<br>abstract fun [validate](../../com.trustless.requests.kyc.retrieveSteps.steps.wrapper/-field-manager/validate.md)(): List&lt;[FieldError](../-field-error/index.md)&gt;<br>returns a list with errors, empty array if the field is valid |
