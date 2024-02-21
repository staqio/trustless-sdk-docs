//[trustless](../../../index.md)/[com.trustless.requests.transfers](../index.md)/[StaqTransferResponseBeneficiary](index.md)

# StaqTransferResponseBeneficiary

[kotlin]\
@Serializable

data class [StaqTransferResponseBeneficiary](index.md)(val name: String, val alias: String? = null, val account: String, val address: String, val bankCode: String, val bankCountry: String, val type: String? = null)

Beneficiary object.

## Constructors

| | |
|---|---|
| [StaqTransferResponseBeneficiary](-staq-transfer-response-beneficiary.md) | [kotlin]<br>constructor(name: String, alias: String? = null, account: String, address: String, bankCode: String, bankCountry: String, type: String? = null) |

## Properties

| Name | Summary |
|---|---|
| [account](account.md) | [kotlin]<br>@SerialName(value = &quot;Account&quot;)<br>val [account](account.md): String<br>Address of Beneficiary |
| [address](address.md) | [kotlin]<br>@SerialName(value = &quot;Address&quot;)<br>val [address](address.md): String<br>Address of Beneficiary |
| [alias](alias.md) | [kotlin]<br>@SerialName(value = &quot;Alias&quot;)<br>val [alias](alias.md): String? = null<br>Alias of Beneficiary |
| [bankCode](bank-code.md) | [kotlin]<br>@SerialName(value = &quot;BankCode&quot;)<br>val [bankCode](bank-code.md): String<br>Bank Code of Beneficiary |
| [bankCountry](bank-country.md) | [kotlin]<br>@SerialName(value = &quot;BankCountry&quot;)<br>val [bankCountry](bank-country.md): String<br>Bank Country of Beneficiary |
| [name](name.md) | [kotlin]<br>@SerialName(value = &quot;Name&quot;)<br>val [name](name.md): String<br>Name of Beneficiary |
| [type](type.md) | [kotlin]<br>@SerialName(value = &quot;Type&quot;)<br>val [type](type.md): String? = null<br>Type of Beneficiary |
