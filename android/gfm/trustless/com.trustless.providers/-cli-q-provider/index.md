//[trustless](../../../index.md)/[com.trustless.providers](../index.md)/[CliQProvider](index.md)

# CliQProvider

interface [CliQProvider](index.md)

#### Inheritors

| |
|---|
| [CliQProviderImp](../../com.trustless.providers.implementations/-cli-q-provider-imp/index.md) |

## Functions

| Name | Summary |
|---|---|
| [createAlias](create-alias.md) | [kotlin]<br>abstract suspend fun [createAlias](create-alias.md)(accountNumber: String, type: String, value: String): [StaqCreateAlias](../../com.trustless.requests.cliq/-staq-create-alias/index.md)<br>Create an alias for chosen account in Cliq |
| [getAliases](get-aliases.md) | [kotlin]<br>abstract suspend fun [getAliases](get-aliases.md)(): List&lt;[StaqAliasDetails](../../com.trustless.requests.cliq/-staq-alias-details/index.md)&gt;<br>Returns all CliQ aliases for the specified customer |
| [getPurposes](get-purposes.md) | [kotlin]<br>abstract suspend fun [getPurposes](get-purposes.md)(params: [GetPurposesRequestParams](../../com.trustless.requests.cliq/-get-purposes-request-params/index.md)): List&lt;[StaqPurpose](../../com.trustless.requests.cliq/-staq-purpose/index.md)&gt;<br>Returns all purpose codes related to cliq customer |
