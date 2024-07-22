//[trustless](../../index.md)/[com.trustless.requests.kyc.retrieveKycStatus](index.md)

# Package-level declarations

## Types

| Name | Summary |
|---|---|
| [Document](-document/index.md) | [kotlin]<br>@Serializable<br>data class [Document](-document/index.md)(val name: String? = null, val documentCode: String? = null, val approved: Boolean? = null, val reason: String? = null, val reasonAr: String? = null) |
| [RetrieveKycStatusResponse](-retrieve-kyc-status-response/index.md) | [kotlin]<br>@Serializable<br>data class [RetrieveKycStatusResponse](-retrieve-kyc-status-response/index.md)(val kycId: String, val customerId: String? = null, val statusCode: String, val status: String, val statusAr: String, val mobileNumber: String, val pendingWalletTimer: String, val active: Boolean, val documents: List&lt;[Document](-document/index.md)&gt;) |
