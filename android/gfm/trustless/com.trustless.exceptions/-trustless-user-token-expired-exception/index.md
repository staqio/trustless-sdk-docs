//[trustless](../../../index.md)/[com.trustless.exceptions](../index.md)/[TrustlessUserTokenExpiredException](index.md)

# TrustlessUserTokenExpiredException

[kotlin]\
class [TrustlessUserTokenExpiredException](index.md) : [TrustlessException](../-trustless-exception/index.md)

This error is thrown when user token has expired due to time, or because it was invalidated on the server

## Properties

| Name | Summary |
|---|---|
| [cause](index.md#-654012527%2FProperties%2F-1818097539) | [kotlin]<br>open val [cause](index.md#-654012527%2FProperties%2F-1818097539): Throwable? |
| [message](index.md#1824300659%2FProperties%2F-1818097539) | [kotlin]<br>open val [message](index.md#1824300659%2FProperties%2F-1818097539): String? |

## Functions

| Name | Summary |
|---|---|
| [addSuppressed](index.md#282858770%2FFunctions%2F-1818097539) | [kotlin]<br>fun [addSuppressed](index.md#282858770%2FFunctions%2F-1818097539)(p0: Throwable) |
| [fillInStackTrace](index.md#-1102069925%2FFunctions%2F-1818097539) | [kotlin]<br>open fun [fillInStackTrace](index.md#-1102069925%2FFunctions%2F-1818097539)(): Throwable |
| [getErrorCode](../-trustless-exception/get-error-code.md) | [kotlin]<br>fun [getErrorCode](../-trustless-exception/get-error-code.md)(): String |
| [getLocalizedMessage](index.md#1043865560%2FFunctions%2F-1818097539) | [kotlin]<br>open fun [getLocalizedMessage](index.md#1043865560%2FFunctions%2F-1818097539)(): String |
| [getStackTrace](index.md#2050903719%2FFunctions%2F-1818097539) | [kotlin]<br>open fun [getStackTrace](index.md#2050903719%2FFunctions%2F-1818097539)(): Array&lt;StackTraceElement&gt; |
| [getSuppressed](index.md#672492560%2FFunctions%2F-1818097539) | [kotlin]<br>fun [getSuppressed](index.md#672492560%2FFunctions%2F-1818097539)(): Array&lt;Throwable&gt; |
| [initCause](index.md#-418225042%2FFunctions%2F-1818097539) | [kotlin]<br>open fun [initCause](index.md#-418225042%2FFunctions%2F-1818097539)(p0: Throwable): Throwable |
| [printStackTrace](index.md#-1769529168%2FFunctions%2F-1818097539) | [kotlin]<br>open fun [printStackTrace](index.md#-1769529168%2FFunctions%2F-1818097539)()<br>open fun [printStackTrace](index.md#1841853697%2FFunctions%2F-1818097539)(p0: PrintStream)<br>open fun [printStackTrace](index.md#1175535278%2FFunctions%2F-1818097539)(p0: PrintWriter) |
| [setStackTrace](index.md#2135801318%2FFunctions%2F-1818097539) | [kotlin]<br>open fun [setStackTrace](index.md#2135801318%2FFunctions%2F-1818097539)(p0: Array&lt;StackTraceElement&gt;) |
