//[trustless](../../../index.md)/[com.trustless.requests.kyc.retrieveSteps.steps](../index.md)/[Page](index.md)

# Page

[kotlin]\
class [Page](index.md)

Class that encapsulates page logic for AllSteps class

## Properties

| Name | Summary |
|---|---|
| [code](code.md) | [kotlin]<br>val [code](code.md): String<br>Page code |
| [fields](fields.md) | [kotlin]<br>val [fields](fields.md): List&lt;[FieldManager](../../com.trustless.requests.kyc.retrieveSteps.steps.wrapper/-field-manager/index.md)&gt;<br>List of all fields on the page |
| [title](title.md) | [kotlin]<br>val [title](title.md): String<br>Title of the page |

## Functions

| Name | Summary |
|---|---|
| [isKyc](is-kyc.md) | [kotlin]<br>fun [isKyc](is-kyc.md)(): Boolean<br>Function is used to check if current page is a KYC scanning process |
| [validate](validate.md) | [kotlin]<br>fun [validate](validate.md)(): ArrayList&lt;[FieldManager](../../com.trustless.requests.kyc.retrieveSteps.steps.wrapper/-field-manager/index.md)&gt;<br>Validates the content of the page |
