//[trustless](../../index.md)/[com.trustless.requests.kyc.retrieveKycStatus](index.md)

# Package-level declarations

## Types

| Name | Summary |
|---|---|
| [Document](-document/index.md) | [kotlin]<br>@Serializable<br>data class [Document](-document/index.md)(val Name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, val DocumentCode: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, val Approved: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null, val Reason: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, val ReasonAr: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null) |
| [RetrieveKycStatusRequest](-retrieve-kyc-status-request/index.md) | [kotlin]<br>class [RetrieveKycStatusRequest](-retrieve-kyc-status-request/index.md) |
| [RetrieveKycStatusResponse](-retrieve-kyc-status-response/index.md) | [kotlin]<br>@Serializable<br>data class [RetrieveKycStatusResponse](-retrieve-kyc-status-response/index.md)(val KycId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), val CustomerId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, val StatusCode: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val Status: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val StatusAr: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val Active: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), val Documents: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[Document](-document/index.md)&gt;) |
