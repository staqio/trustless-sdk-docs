//[trustless](../../../index.md)/[com.trustless.exceptions](../index.md)/[TrustlessException](index.md)

# TrustlessException

open class [TrustlessException](index.md) : Exception

Base class exception, from which all of the other exceptions are inherited This exception is sometimes thrown because of the unknown nature of the error

#### Inheritors

| |
|---|
| [TrustlessAppTokenException](../-trustless-app-token-exception/index.md) |
| [TrustlessCertificateException](../-trustless-certificate-exception/index.md) |
| [TrustlessCustomerIdIsNull](../-trustless-customer-id-is-null/index.md) |
| [TrustlessExceptionListener](../-trustless-exception-listener/index.md) |
| [TrustlessExceptionSecurityProviderIsNotInstalled](../-trustless-exception-security-provider-is-not-installed/index.md) |
| [TrustlessInvalidUsageException](../-trustless-invalid-usage-exception/index.md) |
| [TrustlessKycIdIsNull](../-trustless-kyc-id-is-null/index.md) |
| [TrustlessMalformedResponse](../-trustless-malformed-response/index.md) |
| [TrustlessNotInitializedSdkException](../-trustless-not-initialized-sdk-exception/index.md) |
| [TrustlessPreconditionException](../-trustless-precondition-exception/index.md) |
| [TrustlessUserTokenExpiredException](../-trustless-user-token-expired-exception/index.md) |

## Properties

| Name | Summary |
|---|---|
| [cause](../-trustless-user-token-expired-exception/index.md#-654012527%2FProperties%2F-1818097539) | [kotlin]<br>open val [cause](../-trustless-user-token-expired-exception/index.md#-654012527%2FProperties%2F-1818097539): Throwable? |
| [message](../-trustless-user-token-expired-exception/index.md#1824300659%2FProperties%2F-1818097539) | [kotlin]<br>open val [message](../-trustless-user-token-expired-exception/index.md#1824300659%2FProperties%2F-1818097539): String? |

## Functions

| Name | Summary |
|---|---|
| [addSuppressed](../-trustless-user-token-expired-exception/index.md#282858770%2FFunctions%2F-1818097539) | [kotlin]<br>fun [addSuppressed](../-trustless-user-token-expired-exception/index.md#282858770%2FFunctions%2F-1818097539)(p0: Throwable) |
| [fillInStackTrace](../-trustless-user-token-expired-exception/index.md#-1102069925%2FFunctions%2F-1818097539) | [kotlin]<br>open fun [fillInStackTrace](../-trustless-user-token-expired-exception/index.md#-1102069925%2FFunctions%2F-1818097539)(): Throwable |
| [getErrorCode](get-error-code.md) | [kotlin]<br>fun [getErrorCode](get-error-code.md)(): String |
| [getLocalizedMessage](../-trustless-user-token-expired-exception/index.md#1043865560%2FFunctions%2F-1818097539) | [kotlin]<br>open fun [getLocalizedMessage](../-trustless-user-token-expired-exception/index.md#1043865560%2FFunctions%2F-1818097539)(): String |
| [getStackTrace](../-trustless-user-token-expired-exception/index.md#2050903719%2FFunctions%2F-1818097539) | [kotlin]<br>open fun [getStackTrace](../-trustless-user-token-expired-exception/index.md#2050903719%2FFunctions%2F-1818097539)(): Array&lt;StackTraceElement&gt; |
| [getSuppressed](../-trustless-user-token-expired-exception/index.md#672492560%2FFunctions%2F-1818097539) | [kotlin]<br>fun [getSuppressed](../-trustless-user-token-expired-exception/index.md#672492560%2FFunctions%2F-1818097539)(): Array&lt;Throwable&gt; |
| [initCause](../-trustless-user-token-expired-exception/index.md#-418225042%2FFunctions%2F-1818097539) | [kotlin]<br>open fun [initCause](../-trustless-user-token-expired-exception/index.md#-418225042%2FFunctions%2F-1818097539)(p0: Throwable): Throwable |
| [printStackTrace](../-trustless-user-token-expired-exception/index.md#-1769529168%2FFunctions%2F-1818097539) | [kotlin]<br>open fun [printStackTrace](../-trustless-user-token-expired-exception/index.md#-1769529168%2FFunctions%2F-1818097539)()<br>open fun [printStackTrace](../-trustless-user-token-expired-exception/index.md#1841853697%2FFunctions%2F-1818097539)(p0: PrintStream)<br>open fun [printStackTrace](../-trustless-user-token-expired-exception/index.md#1175535278%2FFunctions%2F-1818097539)(p0: PrintWriter) |
| [setStackTrace](../-trustless-user-token-expired-exception/index.md#2135801318%2FFunctions%2F-1818097539) | [kotlin]<br>open fun [setStackTrace](../-trustless-user-token-expired-exception/index.md#2135801318%2FFunctions%2F-1818097539)(p0: Array&lt;StackTraceElement&gt;) |
