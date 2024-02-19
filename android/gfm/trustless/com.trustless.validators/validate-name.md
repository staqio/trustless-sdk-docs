//[trustless](../../index.md)/[com.trustless.validators](index.md)/[validateName](validate-name.md)

# validateName

[kotlin]\
fun [validateName](validate-name.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), nameCode: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))

Validates a name and throws TrustlessInvalidNameException

#### Parameters

kotlin

| | |
|---|---|
| name | The name to validate. |
| nameCode | A code associated with the name, used in the exception for further identification. |

#### Throws

| | |
|---|---|
| [TrustlessInvalidNameException](../com.trustless.exceptions/-trustless-invalid-name-exception/index.md) | if the name is invalid. |
