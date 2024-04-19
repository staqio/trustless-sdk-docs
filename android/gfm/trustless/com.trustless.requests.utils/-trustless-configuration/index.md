//[trustless](../../../index.md)/[com.trustless.requests.utils](../index.md)/[TrustlessConfiguration](index.md)

# TrustlessConfiguration

class [TrustlessConfiguration](index.md)(clientId: String, clientSecret: String, clientCertificate: [ClientCertificate](../../com.trustless.requests.utils.certificate/-client-certificate/index.md), clientBuilder: OkHttpClient.Builder = OkHttpClient.Builder(), baseUrl: String = &quot;https://sandbox-api.finto.io/api/&quot;, scope: String = &quot;identity kyc accounts cards simulation transfers cliq&quot;)

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
| [TrustlessConfiguration](-trustless-configuration.md) | [kotlin]<br>constructor(clientId: String, clientSecret: String, clientCertificate: [ClientCertificate](../../com.trustless.requests.utils.certificate/-client-certificate/index.md), clientBuilder: OkHttpClient.Builder = OkHttpClient.Builder(), baseUrl: String = &quot;https://sandbox-api.finto.io/api/&quot;, scope: String = &quot;identity kyc accounts cards simulation transfers cliq&quot;) |
