//[trustless](../../../index.md)/[com.trustless.requests.transfers](../index.md)/[StagRequiredDocuments](index.md)

# StagRequiredDocuments

[kotlin]\
@Serializable

data class [StagRequiredDocuments](index.md)(val requiredDocumentCount: Int, val requiredDocumentsList: List&lt;String&gt;, val requiredDocumentsListAr: List&lt;String&gt;, val isDocumentsRequired: List&lt;Boolean?&gt;)

Object with required documents.

## Constructors

| | |
|---|---|
| [StagRequiredDocuments](-stag-required-documents.md) | [kotlin]<br>constructor(requiredDocumentCount: Int, requiredDocumentsList: List&lt;String&gt;, requiredDocumentsListAr: List&lt;String&gt;, isDocumentsRequired: List&lt;Boolean?&gt;) |

## Properties

| Name | Summary |
|---|---|
| [isDocumentsRequired](is-documents-required.md) | [kotlin]<br>@SerialName(value = &quot;IsDocumentsRequired&quot;)<br>val [isDocumentsRequired](is-documents-required.md): List&lt;Boolean?&gt;<br>List of Bool values which mean if the required document is required to continue. |
| [requiredDocumentCount](required-document-count.md) | [kotlin]<br>@SerialName(value = &quot;RequiredDocumentCount&quot;)<br>val [requiredDocumentCount](required-document-count.md): Int<br>Number of required documents |
| [requiredDocumentsList](required-documents-list.md) | [kotlin]<br>@SerialName(value = &quot;RequiredDocumentsList&quot;)<br>val [requiredDocumentsList](required-documents-list.md): List&lt;String&gt;<br>List of names of the required documents |
| [requiredDocumentsListAr](required-documents-list-ar.md) | [kotlin]<br>@SerialName(value = &quot;RequiredDocumentsListAr&quot;)<br>val [requiredDocumentsListAr](required-documents-list-ar.md): List&lt;String&gt;<br>List of arabic names of the required documents |
