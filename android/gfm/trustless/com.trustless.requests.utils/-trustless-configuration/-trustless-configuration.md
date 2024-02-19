//[trustless](../../../index.md)/[com.trustless.requests.utils](../index.md)/[TrustlessConfiguration](index.md)/[TrustlessConfiguration](-trustless-configuration.md)

# TrustlessConfiguration

[kotlin]\
constructor(clientId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), clientSecret: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), clientCertificate: [ClientCertificate](../../com.trustless.requests.utils.certificate/-client-certificate/index.md), clientBuilder: OkHttpClient.Builder = OkHttpClient.Builder())

#### Parameters

kotlin

| | |
|---|---|
| clientId | id of an application client |
| clientSecret | secret of an application |
| clientCertificate | [ClientCertificate](../../com.trustless.requests.utils.certificate/-client-certificate/index.md) certificate from the application |
| clientBuilder | OkHttpClient.Builder Builder of an http client, is useful when you need to add logs to all of the requests |
