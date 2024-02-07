//[trustless](../../../index.md)/[com.trustless.requests.transfers](../index.md)/[StaqTransferResponseBeneficiary](index.md)

# StaqTransferResponseBeneficiary

[kotlin]\
@Serializable

data class [StaqTransferResponseBeneficiary](index.md)(val name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val alias: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, val account: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val address: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val bankCode: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val bankCountry: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val type: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null)

## Constructors

| | |
|---|---|
| [StaqTransferResponseBeneficiary](-staq-transfer-response-beneficiary.md) | [kotlin]<br>constructor(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), alias: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, account: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), address: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), bankCode: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), bankCountry: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), type: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null) |

## Properties

| Name | Summary |
|---|---|
| [account](account.md) | [kotlin]<br>@SerialName(value = &quot;Account&quot;)<br>val [account](account.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [address](address.md) | [kotlin]<br>@SerialName(value = &quot;Address&quot;)<br>val [address](address.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [alias](alias.md) | [kotlin]<br>@SerialName(value = &quot;Alias&quot;)<br>val [alias](alias.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [bankCode](bank-code.md) | [kotlin]<br>@SerialName(value = &quot;BankCode&quot;)<br>val [bankCode](bank-code.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [bankCountry](bank-country.md) | [kotlin]<br>@SerialName(value = &quot;BankCountry&quot;)<br>val [bankCountry](bank-country.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [name](name.md) | [kotlin]<br>@SerialName(value = &quot;Name&quot;)<br>val [name](name.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [type](type.md) | [kotlin]<br>@SerialName(value = &quot;Type&quot;)<br>val [type](type.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
