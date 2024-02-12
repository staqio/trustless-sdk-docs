//[trustless](../../../index.md)/[com.trustless.exceptions](../index.md)/[TrustlessException](index.md)

# TrustlessException

open class [TrustlessException](index.md)(code: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), message: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?) : [Exception](https://developer.android.com/reference/kotlin/java/lang/Exception.html)

#### Inheritors

| |
|---|
| [TrustlessCertificateException](../-trustless-certificate-exception/index.md) |
| [TrustlessCustomerIdIsNull](../-trustless-customer-id-is-null/index.md) |
| [TrustlessExceptionListener](../-trustless-exception-listener/index.md) |
| [TrustlessExceptionSecurityProviderIsNotInstalled](../-trustless-exception-security-provider-is-not-installed/index.md) |
| [TrustlessInvalidJWTAuthHeaderException](../-trustless-invalid-j-w-t-auth-header-exception/index.md) |
| [TrustlessInvalidJWTTokenException](../-trustless-invalid-j-w-t-token-exception/index.md) |
| [TrustlessInvalidUsageException](../-trustless-invalid-usage-exception/index.md) |
| [TrustlessKycIdIsNull](../-trustless-kyc-id-is-null/index.md) |
| [TrustlessMalformedResponse](../-trustless-malformed-response/index.md) |
| [TrustlessNotInitializedSdkException](../-trustless-not-initialized-sdk-exception/index.md) |
| [TrustlessPreconditionException](../-trustless-precondition-exception/index.md) |
| [TrustlessRootDetectedException](../-trustless-root-detected-exception/index.md) |
| [TrustlessServerException](../-trustless-server-exception/index.md) |
| [TrustlessUserIsNotAuthorizedException](../-trustless-user-is-not-authorized-exception/index.md) |
| [TrustlessUserTokenExpiredException](../-trustless-user-token-expired-exception/index.md) |

## Constructors

| | |
|---|---|
| [TrustlessException](-trustless-exception.md) | [kotlin]<br>constructor()constructor(code: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), message: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?) |

## Properties

| Name | Summary |
|---|---|
| [cause](../-trustless-user-token-expired-exception/index.md#-654012527%2FProperties%2F-1818097539) | [kotlin]<br>open val [cause](../-trustless-user-token-expired-exception/index.md#-654012527%2FProperties%2F-1818097539): [Throwable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)? |
| [message](../-trustless-user-token-expired-exception/index.md#1824300659%2FProperties%2F-1818097539) | [kotlin]<br>open val [message](../-trustless-user-token-expired-exception/index.md#1824300659%2FProperties%2F-1818097539): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? |

## Functions

| Name | Summary |
|---|---|
| [addSuppressed](../-trustless-user-token-expired-exception/index.md#282858770%2FFunctions%2F-1818097539) | [kotlin]<br>fun [addSuppressed](../-trustless-user-token-expired-exception/index.md#282858770%2FFunctions%2F-1818097539)(p0: [Throwable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)) |
| [fillInStackTrace](../-trustless-user-token-expired-exception/index.md#-1102069925%2FFunctions%2F-1818097539) | [kotlin]<br>open fun [fillInStackTrace](../-trustless-user-token-expired-exception/index.md#-1102069925%2FFunctions%2F-1818097539)(): [Throwable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html) |
| [getErrorCode](get-error-code.md) | [kotlin]<br>fun [getErrorCode](get-error-code.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [getLocalizedMessage](../-trustless-user-token-expired-exception/index.md#1043865560%2FFunctions%2F-1818097539) | [kotlin]<br>open fun [getLocalizedMessage](../-trustless-user-token-expired-exception/index.md#1043865560%2FFunctions%2F-1818097539)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [getStackTrace](../-trustless-user-token-expired-exception/index.md#2050903719%2FFunctions%2F-1818097539) | [kotlin]<br>open fun [getStackTrace](../-trustless-user-token-expired-exception/index.md#2050903719%2FFunctions%2F-1818097539)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[StackTraceElement](https://developer.android.com/reference/kotlin/java/lang/StackTraceElement.html)&gt; |
| [getSuppressed](../-trustless-user-token-expired-exception/index.md#672492560%2FFunctions%2F-1818097539) | [kotlin]<br>fun [getSuppressed](../-trustless-user-token-expired-exception/index.md#672492560%2FFunctions%2F-1818097539)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[Throwable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)&gt; |
| [initCause](../-trustless-user-token-expired-exception/index.md#-418225042%2FFunctions%2F-1818097539) | [kotlin]<br>open fun [initCause](../-trustless-user-token-expired-exception/index.md#-418225042%2FFunctions%2F-1818097539)(p0: [Throwable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)): [Throwable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html) |
| [printStackTrace](../-trustless-user-token-expired-exception/index.md#-1769529168%2FFunctions%2F-1818097539) | [kotlin]<br>open fun [printStackTrace](../-trustless-user-token-expired-exception/index.md#-1769529168%2FFunctions%2F-1818097539)()<br>open fun [printStackTrace](../-trustless-user-token-expired-exception/index.md#1841853697%2FFunctions%2F-1818097539)(p0: [PrintStream](https://developer.android.com/reference/kotlin/java/io/PrintStream.html))<br>open fun [printStackTrace](../-trustless-user-token-expired-exception/index.md#1175535278%2FFunctions%2F-1818097539)(p0: [PrintWriter](https://developer.android.com/reference/kotlin/java/io/PrintWriter.html)) |
| [setStackTrace](../-trustless-user-token-expired-exception/index.md#2135801318%2FFunctions%2F-1818097539) | [kotlin]<br>open fun [setStackTrace](../-trustless-user-token-expired-exception/index.md#2135801318%2FFunctions%2F-1818097539)(p0: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[StackTraceElement](https://developer.android.com/reference/kotlin/java/lang/StackTraceElement.html)&gt;) |