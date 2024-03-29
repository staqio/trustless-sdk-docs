//[trustless](../../../index.md)/[com.trustless.requests.kyc.retrieveSteps](../index.md)/[InputKYCType](index.md)

# InputKYCType

[kotlin]\
enum [InputKYCType](index.md) : Enum&lt;[InputKYCType](index.md)&gt; 

KYC (Know your customer) field types

## Entries

| | |
|---|---|
| [USER](-u-s-e-r/index.md) | [kotlin]<br>[USER](-u-s-e-r/index.md)<br>The data should be taken from user profile, it is automatically handled by the sdk |
| [INPUT](-i-n-p-u-t/index.md) | [kotlin]<br>[INPUT](-i-n-p-u-t/index.md)<br>User should input this data |
| [UNKNOWN](-u-n-k-n-o-w-n/index.md) | [kotlin]<br>[UNKNOWN](-u-n-k-n-o-w-n/index.md)<br>Unhandled KYC Type |
| [SDK](-s-d-k/index.md) | [kotlin]<br>[SDK](-s-d-k/index.md)<br>The data should be taken from the KYC SDK |
| [DOCUMENT](-d-o-c-u-m-e-n-t/index.md) | [kotlin]<br>[DOCUMENT](-d-o-c-u-m-e-n-t/index.md)<br>Document should be uploaded |

## Properties

| Name | Summary |
|---|---|
| [entries](entries.md) | [kotlin]<br>val [entries](entries.md): EnumEntries&lt;[InputKYCType](index.md)&gt;<br>Returns a representation of an immutable list of all enum entries, in the order they're declared. |
| [name](-d-o-c-u-m-e-n-t/index.md#-372974862%2FProperties%2F-1818097539) | [kotlin]<br>val [name](-d-o-c-u-m-e-n-t/index.md#-372974862%2FProperties%2F-1818097539): String |
| [ordinal](-d-o-c-u-m-e-n-t/index.md#-739389684%2FProperties%2F-1818097539) | [kotlin]<br>val [ordinal](-d-o-c-u-m-e-n-t/index.md#-739389684%2FProperties%2F-1818097539): Int |

## Functions

| Name | Summary |
|---|---|
| [valueOf](value-of.md) | [kotlin]<br>fun [valueOf](value-of.md)(value: String): [InputKYCType](index.md)<br>Returns the enum constant of this type with the specified name. The string must match exactly an identifier used to declare an enum constant in this type. (Extraneous whitespace characters are not permitted.) |
| [values](values.md) | [kotlin]<br>fun [values](values.md)(): Array&lt;[InputKYCType](index.md)&gt;<br>Returns an array containing the constants of this enum type, in the order they're declared. |
