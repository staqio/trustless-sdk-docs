//[trustless](../../../index.md)/[com.trustless.token](../index.md)/[KeyStoreService](index.md)

# KeyStoreService

interface [KeyStoreService](index.md)

#### Inheritors

| |
|---|
| [AndroidKeyStoreService](../-android-key-store-service/index.md) |

## Functions

| Name | Summary |
|---|---|
| [deleteKey](delete-key.md) | []<br>abstract fun [deleteKey](delete-key.md)(keyAlias: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |
| [generateKey](generate-key.md) | []<br>abstract fun [generateKey](generate-key.md)(keyAlias: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), useBiometry: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) |
| [getKey](get-key.md) | []<br>abstract fun [getKey](get-key.md)(keyAlias: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [SecretKey](https://developer.android.com/reference/kotlin/javax/crypto/SecretKey.html) |
| [isKeyPresent](is-key-present.md) | []<br>abstract fun [isKeyPresent](is-key-present.md)(keyAlias: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isUserAuthenticationRequiredForKey](is-user-authentication-required-for-key.md) | []<br>abstract fun [isUserAuthenticationRequiredForKey](is-user-authentication-required-for-key.md)(keyAlias: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
