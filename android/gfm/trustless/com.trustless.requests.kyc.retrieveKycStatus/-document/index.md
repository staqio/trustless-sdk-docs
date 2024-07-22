//[trustless](../../../index.md)/[com.trustless.requests.kyc.retrieveKycStatus](../index.md)/[Document](index.md)

# Document

[kotlin]\
@Serializable

data class [Document](index.md)(val name: String? = null, val documentCode: String? = null, val approved: Boolean? = null, val reason: String? = null, val reasonAr: String? = null)

## Constructors

| | |
|---|---|
| [Document](-document.md) | [kotlin]<br>constructor(name: String? = null, documentCode: String? = null, approved: Boolean? = null, reason: String? = null, reasonAr: String? = null) |

## Properties

| Name | Summary |
|---|---|
| [approved](approved.md) | [kotlin]<br>@SerialName(value = &quot;Approved&quot;)<br>val [approved](approved.md): Boolean? = null |
| [documentCode](document-code.md) | [kotlin]<br>@SerialName(value = &quot;DocumentCode&quot;)<br>val [documentCode](document-code.md): String? = null |
| [name](name.md) | [kotlin]<br>@SerialName(value = &quot;Name&quot;)<br>val [name](name.md): String? = null |
| [reason](reason.md) | [kotlin]<br>@SerialName(value = &quot;Reason&quot;)<br>val [reason](reason.md): String? = null |
| [reasonAr](reason-ar.md) | [kotlin]<br>@SerialName(value = &quot;ReasonAr&quot;)<br>val [reasonAr](reason-ar.md): String? = null |
