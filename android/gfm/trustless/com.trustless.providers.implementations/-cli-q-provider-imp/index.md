//[trustless](../../../index.md)/[com.trustless.providers.implementations](../index.md)/[CliQProviderImp](index.md)

# CliQProviderImp

[kotlin]\
class [CliQProviderImp](index.md) : [CliQProvider](../../com.trustless.providers/-cli-q-provider/index.md)

## Functions

| Name | Summary |
|---|---|
| [createAlias](create-alias.md) | [kotlin]<br>open suspend override fun [createAlias](create-alias.md)(accountNumber: String, type: String, value: String): [StaqCreateAlias](../../com.trustless.requests.cliq/-staq-create-alias/index.md)<br>Create an alias for chosen account in Cliq |
| [getAliases](get-aliases.md) | [kotlin]<br>open suspend override fun [getAliases](get-aliases.md)(): List&lt;[StaqAliasDetails](../../com.trustless.requests.cliq/-staq-alias-details/index.md)&gt;<br>Returns all CliQ aliases for the specified customer |
| [getPurposes](get-purposes.md) | [kotlin]<br>open suspend override fun [getPurposes](get-purposes.md)(params: [GetPurposesRequestParams](../../com.trustless.requests.cliq/-get-purposes-request-params/index.md)): List&lt;[StaqPurpose](../../com.trustless.requests.cliq/-staq-purpose/index.md)&gt;<br>Returns all purpose codes related to cliq customer |
