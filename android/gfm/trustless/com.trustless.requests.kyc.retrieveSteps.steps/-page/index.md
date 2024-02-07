//[trustless](../../../index.md)/[com.trustless.requests.kyc.retrieveSteps.steps](../index.md)/[Page](index.md)

# Page

\
class [Page](index.md)(pageResponse: [RetrieveStep](../../com.trustless.requests.kyc.retrieveSteps/-retrieve-step/index.md), val sourceFields: [SourceFieldsMap](../-source-fields-map/index.md))

## Constructors

| | |
|---|---|
| [Page](-page.md) | <br>constructor(pageResponse: [RetrieveStep](../../com.trustless.requests.kyc.retrieveSteps/-retrieve-step/index.md), sourceFields: [SourceFieldsMap](../-source-fields-map/index.md)) |

## Properties

| Name | Summary |
|---|---|
| [code](code.md) | <br>val [code](code.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [fields](fields.md) | <br>val [fields](fields.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[FieldManager](../../com.trustless.requests.kyc.retrieveSteps.steps.wrapper/-field-manager/index.md)&gt; |
| [sourceFields](source-fields.md) | <br>val [sourceFields](source-fields.md): [SourceFieldsMap](../-source-fields-map/index.md) |
| [title](title.md) | <br>val [title](title.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

## Functions

| Name | Summary |
|---|---|
| [getStructuredFields](get-structured-fields.md) | <br>fun [getStructuredFields](get-structured-fields.md)(): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[FieldWrapper](../../com.trustless.requests.kyc.retrieveSteps.steps.wrapper/-field-wrapper/index.md)&gt; |
| [isKyc](is-kyc.md) | <br>fun [isKyc](is-kyc.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [updateForm](update-form.md) | <br>fun [updateForm](update-form.md)() |
| [validate](validate.md) | <br>fun [validate](validate.md)(): [ArrayList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-array-list/index.html)&lt;[FieldManager](../../com.trustless.requests.kyc.retrieveSteps.steps.wrapper/-field-manager/index.md)&gt; |
