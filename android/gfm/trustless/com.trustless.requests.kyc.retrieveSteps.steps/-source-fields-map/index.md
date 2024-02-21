//[trustless](../../../index.md)/[com.trustless.requests.kyc.retrieveSteps.steps](../index.md)/[SourceFieldsMap](index.md)

# SourceFieldsMap

[kotlin]\
class [SourceFieldsMap](index.md)

A utility class to manage a collection of source fields, supporting various data types. It provides a flexible way to store and retrieve KYC-related data fields, allowing for easy integration with the TRUSTLESS SDK

## Constructors

| | |
|---|---|
| [SourceFieldsMap](-source-fields-map.md) | [kotlin]<br>constructor() |

## Functions

| Name | Summary |
|---|---|
| [clear](clear.md) | [kotlin]<br>fun [clear](clear.md)()<br>Clears all entries from the map, resetting it to an empty state. |
| [get](get.md) | [kotlin]<br>fun [get](get.md)(key: String): Any?<br>Retrieves the value associated with a given key, regardless of its type. |
| [getFile](get-file.md) | [kotlin]<br>fun [getFile](get-file.md)(key: String): File<br>Retrieves a file associated with a given key. Throws an exception if the key is not found or the value is not a File. |
| [getFileOrNull](get-file-or-null.md) | [kotlin]<br>fun [getFileOrNull](get-file-or-null.md)(key: String): File?<br>Retrieves a file associated with a given key, returning null if the key is not found or the value is not a File. |
| [getString](get-string.md) | [kotlin]<br>fun [getString](get-string.md)(key: String): String<br>Retrieves a string value associated with a given key. Throws an exception if the key is not found or the value is not a String. |
| [has](has.md) | [kotlin]<br>fun [has](has.md)(key: String): Boolean<br>Checks if the map contains a specific key. |
| [put](put.md) | [kotlin]<br>fun [put](put.md)(key: String, value: File)<br>Stores a file associated with a given key.<br>[kotlin]<br>fun [put](put.md)(key: String, value: String)<br>Stores a string value associated with a given key. |
