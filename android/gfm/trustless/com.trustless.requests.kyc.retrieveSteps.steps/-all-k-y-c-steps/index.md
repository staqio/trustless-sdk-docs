//[trustless](../../../index.md)/[com.trustless.requests.kyc.retrieveSteps.steps](../index.md)/[AllKYCSteps](index.md)

# AllKYCSteps

[kotlin]\
class [AllKYCSteps](index.md)

A class designed to simplify interactions with the Steps API, facilitating the KYC (Know Your Customer) process.

## Functions

| Name | Summary |
|---|---|
| [getDocumentsMap](get-documents-map.md) | [kotlin]<br>fun [getDocumentsMap](get-documents-map.md)(): Map&lt;String, File&gt;<br>Generates a map of document files to their respective identifiers. This map is used for submitting KYC documents, associating each document with a unique key. |
| [getJSON](get-j-s-o-n.md) | [kotlin]<br>fun [getJSON](get-j-s-o-n.md)(): JSONObject<br>Generates a JSON body for the KYC submission. Iterates over each page, processing its data and compiling it into a JSON object. |
| [getSteps](get-steps.md) | [kotlin]<br>fun [getSteps](get-steps.md)(): List&lt;[Page](../-page/index.md)&gt;<br>Retrieves the KYC steps in a convenient form. Each step is represented as a `Page` class instance, encapsulating the fields. |
