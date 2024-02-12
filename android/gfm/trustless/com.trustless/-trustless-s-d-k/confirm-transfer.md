//[trustless](../../../index.md)/[com.trustless](../index.md)/[TrustlessSDK](index.md)/[confirmTransfer](confirm-transfer.md)

# confirmTransfer

[kotlin]\
suspend fun [confirmTransfer](confirm-transfer.md)(transferId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), documents: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[File](https://developer.android.com/reference/kotlin/java/io/File.html)&gt;? = null): [StaqTransferResponse](../../com.trustless.requests.transfers/-staq-transfer-response/index.md)

[Server Api Reference](https://developer.staq.io/docs/apis/transfers#/Transfers/Confirm%20a%20transfer)

#### Parameters

kotlin

| | |
|---|---|
| transferId | The unique identifier of the transfer |
| documents | A list of documents required to complete the transfer. This list should align with the `requiredDocuments` field in the response object obtained when the transfer is created. |
