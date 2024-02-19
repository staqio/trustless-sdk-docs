//[trustless](../../../index.md)/[com.trustless.requests.utils](../index.md)/[TrustlessConfiguration](index.md)

# TrustlessConfiguration

class [TrustlessConfiguration](index.md)(clientId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), clientSecret: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), clientCertificate: [ClientCertificate](../../com.trustless.requests.utils.certificate/-client-certificate/index.md), clientBuilder: OkHttpClient.Builder = OkHttpClient.Builder())

Configuration of TRUSTLESS SDK

#### Parameters

kotlin

| | |
|---|---|
| clientId | id of an application client |
| clientSecret | secret of an application |
| clientCertificate | [ClientCertificate](../../com.trustless.requests.utils.certificate/-client-certificate/index.md) certificate from the application |
| clientBuilder | OkHttpClient.Builder Builder of an http client, is useful when you need to add logs to all of the requests |

## Constructors

| | |
|---|---|
| [TrustlessConfiguration](-trustless-configuration.md) | [kotlin]<br>constructor(clientId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), clientSecret: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), clientCertificate: [ClientCertificate](../../com.trustless.requests.utils.certificate/-client-certificate/index.md), clientBuilder: OkHttpClient.Builder = OkHttpClient.Builder()) |
