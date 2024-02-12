//[trustless](../../../index.md)/[com.trustless](../index.md)/[TrustlessSDK](index.md)/[createAlias](create-alias.md)

# createAlias

[kotlin]\
suspend fun [createAlias](create-alias.md)(accountNumber: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), type: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [StaqCreateAlias](../../com.trustless.requests.cliq/-staq-create-alias/index.md)

Create an alias for chosen account in Cliq

[Server Api Reference](https://developer.staq.io/docs/apis/cliq#/Aliases/Create%20an%20cliq%20alias)

#### Parameters

kotlin

| | |
|---|---|
| accountNumber | Bank account number of the customer |
| type | Cliq alias type. Choose between ALIAS or MOBL ENUM:  ALIAS, MOBL |
| value | Cliq alias value. |
