//[trustless](../../../index.md)/[com.trustless.utils.security](../index.md)/[AppSecurityManager](index.md)

# AppSecurityManager

[kotlin]\
class [AppSecurityManager](index.md)(context: Context)

## Constructors

| | |
|---|---|
| [AppSecurityManager](-app-security-manager.md) | [kotlin]<br>constructor(context: Context) |

## Types

| Name | Summary |
|---|---|
| [SecurityViolationListener](-security-violation-listener/index.md) | [kotlin]<br>interface [SecurityViolationListener](-security-violation-listener/index.md) |

## Properties

| Name | Summary |
|---|---|
| [listener](listener.md) | [kotlin]<br>var [listener](listener.md): [AppSecurityManager.SecurityViolationListener](-security-violation-listener/index.md)? |

## Functions

| Name | Summary |
|---|---|
| [disableScreenshots](disable-screenshots.md) | [kotlin]<br>fun [disableScreenshots](disable-screenshots.md)(activity: Activity) |
| [handleSecurityViolation](handle-security-violation.md) | [kotlin]<br>fun [handleSecurityViolation](handle-security-violation.md)(violationType: [SecurityViolationType](../-security-violation-type/index.md)) |
| [isRootedDevice](is-rooted-device.md) | [kotlin]<br>fun [isRootedDevice](is-rooted-device.md)(): Boolean |
| [isVpnActive](is-vpn-active.md) | [kotlin]<br>fun [isVpnActive](is-vpn-active.md)(): Boolean |
