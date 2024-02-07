//[trustless](../../../index.md)/[com.trustless.requests.kyc.retrieveKycStatus](../index.md)/[RetrieveKycStatusResponse](index.md)

# RetrieveKycStatusResponse

[kotlin]\
@Serializable

data class [RetrieveKycStatusResponse](index.md)(val KycId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), val CustomerId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, val StatusCode: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val Status: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val StatusAr: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val Active: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), val Documents: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[Document](../-document/index.md)&gt;)

## Constructors

| | |
|---|---|
| [RetrieveKycStatusResponse](-retrieve-kyc-status-response.md) | [kotlin]<br>constructor(KycId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), CustomerId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, StatusCode: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), Status: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), StatusAr: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), Active: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), Documents: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[Document](../-document/index.md)&gt;) |

## Properties

| Name | Summary |
|---|---|
| [Active](-active.md) | [kotlin]<br>val [Active](-active.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [CustomerId](-customer-id.md) | [kotlin]<br>val [CustomerId](-customer-id.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [Documents](-documents.md) | [kotlin]<br>val [Documents](-documents.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[Document](../-document/index.md)&gt; |
| [KycId](-kyc-id.md) | [kotlin]<br>val [KycId](-kyc-id.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [Status](-status.md) | [kotlin]<br>val [Status](-status.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [StatusAr](-status-ar.md) | [kotlin]<br>val [StatusAr](-status-ar.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [StatusCode](-status-code.md) | [kotlin]<br>val [StatusCode](-status-code.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
