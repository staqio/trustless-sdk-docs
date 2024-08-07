//[trustless](../../../index.md)/[com.trustless.requests.kyc.deviceStatus](../index.md)/[GetDeviceStatusResponse](index.md)

# GetDeviceStatusResponse

[kotlin]\
@Serializable

data class [GetDeviceStatusResponse](index.md)(val firstLoginDateTime: String, val lastLoginDateTime: String, val deviceStatus: String, val pendingTimer: String? = null)

## Constructors

| | |
|---|---|
| [GetDeviceStatusResponse](-get-device-status-response.md) | [kotlin]<br>constructor(firstLoginDateTime: String, lastLoginDateTime: String, deviceStatus: String, pendingTimer: String? = null) |

## Properties

| Name | Summary |
|---|---|
| [deviceStatus](device-status.md) | [kotlin]<br>@SerialName(value = &quot;DeviceStatus&quot;)<br>val [deviceStatus](device-status.md): String |
| [firstLoginDateTime](first-login-date-time.md) | [kotlin]<br>@SerialName(value = &quot;FirstLoginDateTime&quot;)<br>val [firstLoginDateTime](first-login-date-time.md): String |
| [lastLoginDateTime](last-login-date-time.md) | [kotlin]<br>@SerialName(value = &quot;LastLoginDateTime&quot;)<br>val [lastLoginDateTime](last-login-date-time.md): String |
| [pendingTimer](pending-timer.md) | [kotlin]<br>@SerialName(value = &quot;PendingTimer&quot;)<br>val [pendingTimer](pending-timer.md): String? = null |
