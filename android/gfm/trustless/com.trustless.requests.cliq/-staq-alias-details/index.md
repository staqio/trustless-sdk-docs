//[trustless](../../../index.md)/[com.trustless.requests.cliq](../index.md)/[StaqAliasDetails](index.md)

# StaqAliasDetails

\
@Serializable

data class [StaqAliasDetails](index.md)(val type: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val value: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val startDate: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val expirationDate: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val status: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val accounts: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[StaqAccount](../-staq-account/index.md)&gt;)

## Constructors

| | |
|---|---|
| [StaqAliasDetails](-staq-alias-details.md) | <br>constructor(type: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), startDate: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), expirationDate: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), status: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), accounts: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[StaqAccount](../-staq-account/index.md)&gt;) |

## Properties

| Name | Summary |
|---|---|
| [accounts](accounts.md) | <br>@SerialName(value = &quot;Accounts&quot;)<br>val [accounts](accounts.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[StaqAccount](../-staq-account/index.md)&gt; |
| [expirationDate](expiration-date.md) | <br>@SerialName(value = &quot;ExpirationDate&quot;)<br>val [expirationDate](expiration-date.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [startDate](start-date.md) | <br>@SerialName(value = &quot;StartDate&quot;)<br>val [startDate](start-date.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [status](status.md) | <br>@SerialName(value = &quot;Status&quot;)<br>val [status](status.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [type](type.md) | <br>@SerialName(value = &quot;Type&quot;)<br>val [type](type.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [value](value.md) | <br>@SerialName(value = &quot;Value&quot;)<br>val [value](value.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
