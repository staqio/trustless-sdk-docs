//[trustless](../../../index.md)/[com.trustless.token](../index.md)/[AndroidKeyStoreService](index.md)

# AndroidKeyStoreService

[]\
class [AndroidKeyStoreService](index.md) : [KeyStoreService](../-key-store-service/index.md)

## Constructors

| | |
|---|---|
| [AndroidKeyStoreService](-android-key-store-service.md) | []<br>constructor() |

## Types

| Name | Summary |
|---|---|
| [Companion](-companion/index.md) | []<br>object [Companion](-companion/index.md) |

## Functions

| Name | Summary |
|---|---|
| [deleteKey](delete-key.md) | []<br>open override fun [deleteKey](delete-key.md)(keyAlias: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |
| [generateKey](generate-key.md) | []<br>open override fun [generateKey](generate-key.md)(keyAlias: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), useBiometry: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) |
| [getKey](get-key.md) | []<br>open override fun [getKey](get-key.md)(keyAlias: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [SecretKey](https://developer.android.com/reference/kotlin/javax/crypto/SecretKey.html) |
| [isKeyPresent](is-key-present.md) | []<br>open override fun [isKeyPresent](is-key-present.md)(keyAlias: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isUserAuthenticationRequiredForKey](is-user-authentication-required-for-key.md) | []<br>open override fun [isUserAuthenticationRequiredForKey](is-user-authentication-required-for-key.md)(keyAlias: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
