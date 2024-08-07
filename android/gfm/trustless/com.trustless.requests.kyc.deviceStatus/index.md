//[trustless](../../index.md)/[com.trustless.requests.kyc.deviceStatus](index.md)

# Package-level declarations

## Types

| Name | Summary |
|---|---|
| [GetDeviceStatusParams](-get-device-status-params/index.md) | [kotlin]<br>class [GetDeviceStatusParams](-get-device-status-params/index.md)(deviceId: String) : [JSONParamsBuilder](../com.trustless.params/-j-s-o-n-params-builder/index.md) |
| [GetDeviceStatusResponse](-get-device-status-response/index.md) | [kotlin]<br>@Serializable<br>data class [GetDeviceStatusResponse](-get-device-status-response/index.md)(val firstLoginDateTime: String, val lastLoginDateTime: String, val deviceStatus: String, val pendingTimer: String? = null) |
