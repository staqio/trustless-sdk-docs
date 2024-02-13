//[trustless](../../../index.md)/[com.trustless](../index.md)/[TrustlessSDK](index.md)/[approveKyc](approve-kyc.md)

# approveKyc

[kotlin]\
suspend fun [approveKyc](approve-kyc.md)()

Update status of customer by kycId (DEV ONLY)

[Server Api Reference](https://developer.staq.io/docs/apis/simulation#/KYC/Update%20KYC%20Status)

#### Throws

| | |
|---|---|
| [TrustlessException](../../com.trustless.exceptions/-trustless-exception/index.md) | Is thrown when the server returns custom error, or when error was not expected by the SDK |
| [TrustlessAppTokenException](../../com.trustless.exceptions/-trustless-app-token-exception/index.md) | Is thrown when the token expires, either due to time period or server forced expiration |
| [TrustlessMalformedResponse](../../com.trustless.exceptions/-trustless-malformed-response/index.md) | Is thrown when server returned unexpected format of the data |
| CancellationException | Is thrown usually when the developer cancels the coroutine |
