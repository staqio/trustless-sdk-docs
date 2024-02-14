//[trustless](../../../index.md)/[com.trustless.requests.kyc.retrieveSteps.steps](../index.md)/[AllKYCSteps](index.md)/[getDocumentsMap](get-documents-map.md)

# getDocumentsMap

[kotlin]\
fun [getDocumentsMap](get-documents-map.md)(): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [File](https://developer.android.com/reference/kotlin/java/io/File.html)&gt;

Generates a map of document files to their respective identifiers. This map is used for submitting KYC documents, associating each document with a unique key.

#### Return

A Map<String, File>, where each key is a unique identifier for the document, and the value is the File itself.
