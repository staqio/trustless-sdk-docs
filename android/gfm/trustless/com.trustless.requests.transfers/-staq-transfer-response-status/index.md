//[trustless](../../../index.md)/[com.trustless.requests.transfers](../index.md)/[StaqTransferResponseStatus](index.md)

# StaqTransferResponseStatus

[kotlin]\
@Serializable

data class [StaqTransferResponseStatus](index.md)(val id: Int, val code: String, val name: String, val label: String, val labelAr: String)

Status response object

## Constructors

| | |
|---|---|
| [StaqTransferResponseStatus](-staq-transfer-response-status.md) | [kotlin]<br>constructor(id: Int, code: String, name: String, label: String, labelAr: String) |

## Properties

| Name | Summary |
|---|---|
| [code](code.md) | [kotlin]<br>@SerialName(value = &quot;Code&quot;)<br>val [code](code.md): String<br>The code of status |
| [id](id.md) | [kotlin]<br>@SerialName(value = &quot;Id&quot;)<br>val [id](id.md): Int<br>The unique transaction id |
| [label](label.md) | [kotlin]<br>@SerialName(value = &quot;Label&quot;)<br>val [label](label.md): String<br>The label of status |
| [labelAr](label-ar.md) | [kotlin]<br>@SerialName(value = &quot;LabelAr&quot;)<br>val [labelAr](label-ar.md): String<br>The label of status in Arabic |
| [name](name.md) | [kotlin]<br>@SerialName(value = &quot;Name&quot;)<br>val [name](name.md): String<br>The name of status |
