//[trustless](../../../index.md)/[com.trustless.requests.kyc.retrieveSteps.steps.fields](../index.md)/[KYCBaseField](index.md)

# KYCBaseField

sealed class [KYCBaseField](index.md) : [KYCField](../../com.trustless.requests.kyc.retrieveSteps.steps.wrapper/-k-y-c-field/index.md)

#### Inheritors

| |
|---|
| [KYCBooleanField](../-k-y-c-boolean-field/index.md) |
| [KYCDateField](../-k-y-c-date-field/index.md) |
| [KYCDocumentField](../-k-y-c-document-field/index.md) |
| [KYCIntegerField](../-k-y-c-integer-field/index.md) |
| [KYCListOfValuesField](../-k-y-c-list-of-values-field/index.md) |
| [KYCProofDocumentField](../-k-y-c-proof-document-field/index.md) |
| [KYCTextField](../-k-y-c-text-field/index.md) |

## Properties

| Name | Summary |
|---|---|
| [code](code.md) | [kotlin]<br>open override val [code](code.md): String<br>a code for the field, primarily used internally |
| [dependentFields](dependent-fields.md) | [kotlin]<br>open override val [dependentFields](dependent-fields.md): List&lt;String&gt;<br>a list of fields that this field is depended on |
| [isFromSDK](is-from-s-d-k.md) | [kotlin]<br>open override val [isFromSDK](is-from-s-d-k.md): Boolean<br>is the source type of the filed is SDK |
| [isRequired](is-required.md) | [kotlin]<br>open override val [isRequired](is-required.md): Boolean<br>if the field is required to fill in |
| [isVisible](is-visible.md) | [kotlin]<br>open override var [isVisible](is-visible.md): Boolean<br>if the field should be visible, with the current other fields values. For example, if user answers a field with a question &quot;Are you a student?&quot;: &quot;No&quot;, the other field's property isVisible with the question &quot;What year are you?&quot;, will be automatically set to false. |
| [labelAr](label-ar.md) | [kotlin]<br>open override val [labelAr](label-ar.md): String<br>Arabic label for a field |
| [labelEn](label-en.md) | [kotlin]<br>open override val [labelEn](label-en.md): String<br>English label for a field |
| [readOnly](read-only.md) | [kotlin]<br>open override val [readOnly](read-only.md): Boolean<br>if a field read only |
| [source](source.md) | [kotlin]<br>open override val [source](source.md): [KYCInputType](../../com.trustless.requests.kyc.retrieveSteps/-k-y-c-input-type/index.md)<br>the source of data for the field, could be: USER, INPUT, UNKNOWN, SDK, DOCUMENT |
| [sourceField](source-field.md) | [kotlin]<br>open override val [sourceField](source-field.md): String<br>A key for sourceFields object to get the data from |
| [webViewUrl](web-view-url.md) | [kotlin]<br>open override val [webViewUrl](web-view-url.md): String<br>url that should be opened in the webview |

## Functions

| Name | Summary |
|---|---|
| [isValid](../../com.trustless.requests.kyc.retrieveSteps.steps.wrapper/-k-y-c-field/is-valid.md) | [kotlin]<br>abstract fun [isValid](../../com.trustless.requests.kyc.retrieveSteps.steps.wrapper/-k-y-c-field/is-valid.md)(): Boolean<br>if the current field has valid data |
| [validate](../../com.trustless.requests.kyc.retrieveSteps.steps.wrapper/-k-y-c-field/validate.md) | [kotlin]<br>abstract fun [validate](../../com.trustless.requests.kyc.retrieveSteps.steps.wrapper/-k-y-c-field/validate.md)(): List&lt;[KYCFieldError](../-k-y-c-field-error/index.md)&gt;<br>returns a list with errors, empty array if the field is valid |
