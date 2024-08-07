//[trustless](../../../index.md)/[com.trustless.providers.implementations](../index.md)/[VerificationProviderImpl](index.md)

# VerificationProviderImpl

[kotlin]\
class [VerificationProviderImpl](index.md) : [VerificationProvider](../../com.trustless.providers/-verification-provider/index.md)

## Functions

| Name | Summary |
|---|---|
| [generateOtpCode](generate-otp-code.md) | [kotlin]<br>open suspend override fun [generateOtpCode](generate-otp-code.md)(params: [GenerateOtpParams](../../com.trustless.requests.verification/-generate-otp-params/index.md)): [GenerateOtpResponse](../../com.trustless.requests.verification/-generate-otp-response/index.md) |
| [sendOtp](send-otp.md) | [kotlin]<br>open suspend override fun [sendOtp](send-otp.md)(params: [OtpSendParams](../../com.trustless.requests.verification/-otp-send-params/index.md)): [OtpSendResponse](../../com.trustless.requests.verification/-otp-send-response/index.md) |
| [verifyOtp](verify-otp.md) | [kotlin]<br>open suspend override fun [verifyOtp](verify-otp.md)(params: [OtpVerifyParams](../../com.trustless.requests.verification/-otp-verify-params/index.md)): [OtpVerifyResponse](../../com.trustless.requests.verification/-otp-verify-response/index.md) |
