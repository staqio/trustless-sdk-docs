//[trustless](../../../index.md)/[com.trustless.requests.kyc.retrieveKycStatus](../index.md)/[RetrieveKycStatusResponse](index.md)

# RetrieveKycStatusResponse

[kotlin]\
@Serializable

data class [RetrieveKycStatusResponse](index.md)(val kycId: String, val customerId: String? = null, val statusCode: String, val status: String, val statusAr: String, val mobileNumber: String, val pendingWalletTimer: String, val active: Boolean, val documents: List&lt;[Document](../-document/index.md)&gt;)

## Constructors

| | |
|---|---|
| [RetrieveKycStatusResponse](-retrieve-kyc-status-response.md) | [kotlin]<br>constructor(kycId: String, customerId: String? = null, statusCode: String, status: String, statusAr: String, mobileNumber: String, pendingWalletTimer: String, active: Boolean, documents: List&lt;[Document](../-document/index.md)&gt;) |

## Properties

| Name | Summary |
|---|---|
| [active](active.md) | [kotlin]<br>@SerialName(value = &quot;Active&quot;)<br>val [active](active.md): Boolean |
| [customerId](customer-id.md) | [kotlin]<br>@SerialName(value = &quot;CustomerId&quot;)<br>val [customerId](customer-id.md): String? = null |
| [documents](documents.md) | [kotlin]<br>@SerialName(value = &quot;Documents&quot;)<br>val [documents](documents.md): List&lt;[Document](../-document/index.md)&gt; |
| [kycId](kyc-id.md) | [kotlin]<br>@SerialName(value = &quot;KycId&quot;)<br>val [kycId](kyc-id.md): String |
| [mobileNumber](mobile-number.md) | [kotlin]<br>@SerialName(value = &quot;MobileNumber&quot;)<br>val [mobileNumber](mobile-number.md): String |
| [pendingWalletTimer](pending-wallet-timer.md) | [kotlin]<br>@SerialName(value = &quot;PendingWalletTimer&quot;)<br>val [pendingWalletTimer](pending-wallet-timer.md): String |
| [status](status.md) | [kotlin]<br>@SerialName(value = &quot;Status&quot;)<br>val [status](status.md): String |
| [statusAr](status-ar.md) | [kotlin]<br>@SerialName(value = &quot;StatusAr&quot;)<br>val [statusAr](status-ar.md): String |
| [statusCode](status-code.md) | [kotlin]<br>@SerialName(value = &quot;StatusCode&quot;)<br>val [statusCode](status-code.md): String |
