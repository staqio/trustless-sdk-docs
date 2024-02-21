//[trustless](../../index.md)/[com.trustless.requests.cliq](index.md)

# Package-level declarations

## Types

| Name | Summary |
|---|---|
| [CreateCliqParams](-create-cliq-params/index.md) | [kotlin]<br>class [CreateCliqParams](-create-cliq-params/index.md)(type: String, value: String) : [JSONParamsBuilder](../com.trustless.params/-j-s-o-n-params-builder/index.md) |
| [GetPurposesRequestParams](-get-purposes-request-params/index.md) | [kotlin]<br>class [GetPurposesRequestParams](-get-purposes-request-params/index.md)(aliasType: String, alias: String) : [UrlQueryParams](../com.trustless.queryParams/-url-query-params/index.md)<br>Get purposes params |
| [StaqAccount](-staq-account/index.md) | [kotlin]<br>@Serializable<br>data class [StaqAccount](-staq-account/index.md)(val currency: String, val openingDate: String, val closingDate: String, val iban: String, val isDefault: Boolean)<br>Account object |
| [StaqAliasDetails](-staq-alias-details/index.md) | [kotlin]<br>@Serializable<br>data class [StaqAliasDetails](-staq-alias-details/index.md)(val type: String, val value: String, val startDate: String, val expirationDate: String, val status: String, val accounts: List&lt;[StaqAccount](-staq-account/index.md)&gt;)<br>Alias Details Object |
| [StaqAliasType](-staq-alias-type/index.md) | [kotlin]<br>enum [StaqAliasType](-staq-alias-type/index.md) : Enum&lt;[StaqAliasType](-staq-alias-type/index.md)&gt; |
| [StaqCreateAlias](-staq-create-alias/index.md) | [kotlin]<br>@Serializable<br>data class [StaqCreateAlias](-staq-create-alias/index.md)(val iban: String, val alias: String, val isDefault: Boolean)<br>Create alias object |
| [StaqPurpose](-staq-purpose/index.md) | [kotlin]<br>@Serializable<br>data class [StaqPurpose](-staq-purpose/index.md)(val purposeCode: String, val purposeCodeLabelAr: String, val purposeCodeLabelEn: String)<br>Purpose object |
