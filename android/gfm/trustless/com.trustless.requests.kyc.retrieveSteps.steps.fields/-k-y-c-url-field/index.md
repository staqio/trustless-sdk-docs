//[trustless](../../../index.md)/[com.trustless.requests.kyc.retrieveSteps.steps.fields](../index.md)/[KYCUrlField](index.md)

# KYCUrlField

[kotlin]\
class [KYCUrlField](index.md) : [KYCListOfValuesField](../-k-y-c-list-of-values-field/index.md)

## Properties

| Name | Summary |
|---|---|
| [code](../-k-y-c-base-field/code.md) | [kotlin]<br>open override val [code](../-k-y-c-base-field/code.md): String<br>a code for the field, primarily used internally |
| [dependentFields](../-k-y-c-base-field/dependent-fields.md) | [kotlin]<br>open override val [dependentFields](../-k-y-c-base-field/dependent-fields.md): List&lt;String&gt;<br>a list of fields that this field is depended on |
| [isFromSDK](../-k-y-c-base-field/is-from-s-d-k.md) | [kotlin]<br>open override val [isFromSDK](../-k-y-c-base-field/is-from-s-d-k.md): Boolean<br>is the source type of the filed is SDK |
| [isRequired](../-k-y-c-base-field/is-required.md) | [kotlin]<br>open override val [isRequired](../-k-y-c-base-field/is-required.md): Boolean<br>if the field is required to fill in |
| [isVisible](../-k-y-c-base-field/is-visible.md) | [kotlin]<br>open override var [isVisible](../-k-y-c-base-field/is-visible.md): Boolean<br>if the field should be visible, with the current other fields values. For example, if user answers a field with a question &quot;Are you a student?&quot;: &quot;No&quot;, the other field's property isVisible with the question &quot;What year are you?&quot;, will be automatically set to false. |
| [labelAr](../-k-y-c-base-field/label-ar.md) | [kotlin]<br>open override val [labelAr](../-k-y-c-base-field/label-ar.md): String<br>Arabic label for a field |
| [labelEn](../-k-y-c-base-field/label-en.md) | [kotlin]<br>open override val [labelEn](../-k-y-c-base-field/label-en.md): String<br>English label for a field |
| [readOnly](../-k-y-c-base-field/read-only.md) | [kotlin]<br>open override val [readOnly](../-k-y-c-base-field/read-only.md): Boolean<br>if a field read only |
| [source](../-k-y-c-base-field/source.md) | [kotlin]<br>open override val [source](../-k-y-c-base-field/source.md): [KYCInputType](../../com.trustless.requests.kyc.retrieveSteps/-k-y-c-input-type/index.md)<br>the source of data for the field, could be: USER, INPUT, UNKNOWN, SDK, DOCUMENT |
| [sourceField](../-k-y-c-base-field/source-field.md) | [kotlin]<br>open override val [sourceField](../-k-y-c-base-field/source-field.md): String<br>A key for sourceFields object to get the data from |
| [webViewUrl](../-k-y-c-base-field/web-view-url.md) | [kotlin]<br>open override val [webViewUrl](../-k-y-c-base-field/web-view-url.md): String<br>url that should be opened in the webview |

## Functions

| Name | Summary |
|---|---|
| [getChoicesAr](get-choices-ar.md) | [kotlin]<br>open override fun [getChoicesAr](get-choices-ar.md)(): Map&lt;String, String&gt;<br>Returns Arabic Choices |
| [getChoicesEn](get-choices-en.md) | [kotlin]<br>open override fun [getChoicesEn](get-choices-en.md)(): Map&lt;String, String&gt;<br>Returns English Choices |
| [getCurrentValueAr](../-k-y-c-list-of-values-field/get-current-value-ar.md) | [kotlin]<br>fun [getCurrentValueAr](../-k-y-c-list-of-values-field/get-current-value-ar.md)(): String<br>Gets Arabic Value |
| [getCurrentValueEn](../-k-y-c-list-of-values-field/get-current-value-en.md) | [kotlin]<br>fun [getCurrentValueEn](../-k-y-c-list-of-values-field/get-current-value-en.md)(): String<br>Gets English value |
| [getValue](../-k-y-c-list-of-values-field/get-value.md) | [kotlin]<br>fun [getValue](../-k-y-c-list-of-values-field/get-value.md)(): String<br>Gets Value Key of a selection |
| [getValueFromDependentField](get-value-from-dependent-field.md) | [kotlin]<br>fun [getValueFromDependentField](get-value-from-dependent-field.md)(): String?<br>Returns value from dependent field |
| [hasDependentFieldChanged](has-dependent-field-changed.md) | [kotlin]<br>fun [hasDependentFieldChanged](has-dependent-field-changed.md)(): Boolean |
| [isValid](../-k-y-c-list-of-values-field/is-valid.md) | [kotlin]<br>open override fun [isValid](../-k-y-c-list-of-values-field/is-valid.md)(): Boolean<br>if the current field has valid data |
| [putValue](../-k-y-c-list-of-values-field/put-value.md) | [kotlin]<br>fun [putValue](../-k-y-c-list-of-values-field/put-value.md)(value: String)<br>Sets value for a selection, or not if the value is not valid |
| [setChoices](set-choices.md) | [kotlin]<br>fun [setChoices](set-choices.md)(choicesEn: Map&lt;String, String&gt;, choicesAr: Map&lt;String, String&gt;)<br>Sets choices for Url field |
| [validate](../-k-y-c-list-of-values-field/validate.md) | [kotlin]<br>open override fun [validate](../-k-y-c-list-of-values-field/validate.md)(): List&lt;[KYCFieldError](../-k-y-c-field-error/index.md)&gt;<br>returns a list with errors, empty array if the field is valid |
