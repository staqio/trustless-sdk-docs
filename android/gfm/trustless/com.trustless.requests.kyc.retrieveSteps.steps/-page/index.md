//[trustless](../../../index.md)/[com.trustless.requests.kyc.retrieveSteps.steps](../index.md)/[Page](index.md)

# Page

[kotlin]\
class [Page](index.md)

Class that is encapsulates page logic for AllSteps class

## Properties

| Name | Summary |
|---|---|
| [code](code.md) | [kotlin]<br>val [code](code.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>Page code |
| [fields](fields.md) | [kotlin]<br>val [fields](fields.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[FieldManager](../../com.trustless.requests.kyc.retrieveSteps.steps.wrapper/-field-manager/index.md)&gt;<br>List of all fields on the page |
| [title](title.md) | [kotlin]<br>val [title](title.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>Title of the page |

## Functions

| Name | Summary |
|---|---|
| [isKyc](is-kyc.md) | [kotlin]<br>fun [isKyc](is-kyc.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Function is used to check if current page is a KYC scanning process |
| [validate](validate.md) | [kotlin]<br>fun [validate](validate.md)(): [ArrayList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-array-list/index.html)&lt;[FieldManager](../../com.trustless.requests.kyc.retrieveSteps.steps.wrapper/-field-manager/index.md)&gt;<br>Validates the content of the page |
