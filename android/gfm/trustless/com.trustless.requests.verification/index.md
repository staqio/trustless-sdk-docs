//[trustless](../../index.md)/[com.trustless.requests.verification](index.md)

# Package-level declarations

## Types

| Name | Summary |
|---|---|
| [GenerateOtpParams](-generate-otp-params/index.md) | [kotlin]<br>class [GenerateOtpParams](-generate-otp-params/index.md)(locale: String, length: Int, type: String) : [JSONParamsBuilder](../com.trustless.params/-j-s-o-n-params-builder/index.md) |
| [GenerateOtpResponse](-generate-otp-response/index.md) | [kotlin]<br>@Serializable<br>data class [GenerateOtpResponse](-generate-otp-response/index.md) |
| [OtpSendParams](-otp-send-params/index.md) | [kotlin]<br>class [OtpSendParams](-otp-send-params/index.md)(to: String, channel: String, locale: String, length: Int, type: String) : [JSONParamsBuilder](../com.trustless.params/-j-s-o-n-params-builder/index.md) |
| [OtpSendResponse](-otp-send-response/index.md) | [kotlin]<br>@Serializable<br>data class [OtpSendResponse](-otp-send-response/index.md)(val id: String, val sequence: Int) |
| [OtpVerifyParams](-otp-verify-params/index.md) | [kotlin]<br>class [OtpVerifyParams](-otp-verify-params/index.md)(to: String, channel: String, code: String) : [JSONParamsBuilder](../com.trustless.params/-j-s-o-n-params-builder/index.md) |
| [OtpVerifyResponse](-otp-verify-response/index.md) | [kotlin]<br>@Serializable<br>data class [OtpVerifyResponse](-otp-verify-response/index.md)(val code: String) |
