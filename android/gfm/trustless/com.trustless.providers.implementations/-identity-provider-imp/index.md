//[trustless](../../../index.md)/[com.trustless.providers.implementations](../index.md)/[IdentityProviderImp](index.md)

# IdentityProviderImp

[kotlin]\
class [IdentityProviderImp](index.md) : [IdentityProvider](../../com.trustless.providers/-identity-provider/index.md)

## Functions

| Name | Summary |
|---|---|
| [canLoginUsingSavedToken](can-login-using-saved-token.md) | [kotlin]<br>open suspend override fun [canLoginUsingSavedToken](can-login-using-saved-token.md)(): Boolean |
| [canLoginUsingSavedTokenUsingBiometry](can-login-using-saved-token-using-biometry.md) | [kotlin]<br>open override fun [canLoginUsingSavedTokenUsingBiometry](can-login-using-saved-token-using-biometry.md)(): Boolean |
| [clearPasscodeAndBiometry](clear-passcode-and-biometry.md) | [kotlin]<br>open override fun [clearPasscodeAndBiometry](clear-passcode-and-biometry.md)() |
| [extractSavedToken](extract-saved-token.md) | [kotlin]<br>open suspend override fun [extractSavedToken](extract-saved-token.md)(passcode: String) |
| [isPasscodeCorrect](is-passcode-correct.md) | [kotlin]<br>open suspend override fun [isPasscodeCorrect](is-passcode-correct.md)(passcode: String): Boolean |
| [isUserAuthenticated](is-user-authenticated.md) | [kotlin]<br>open override fun [isUserAuthenticated](is-user-authenticated.md)(): Boolean |
| [login](login.md) | [kotlin]<br>open suspend override fun [login](login.md)(params: [UserTokenRequestParams](../../com.trustless.requests.identity.userToken/-user-token-request-params/index.md), useBiometry: Boolean): [StaqUserTokenResponse](../../com.trustless.requests.identity/-staq-user-token-response/index.md)<br>Returns access token for an application or user |
| [login2FA](login2-f-a.md) | [kotlin]<br>open suspend override fun [login2FA](login2-f-a.md)(params: &lt;Error class: unknown class&gt;): [StaqUserTokenResponse](../../com.trustless.requests.identity/-staq-user-token-response/index.md) |
| [logout](logout.md) | [kotlin]<br>open suspend override fun [logout](logout.md)()<br>This endpoint is used to invalidate the token, and to remove the data of the current user from the memory. Refer to the Advanced section about deinitialization for more details |
| [otp2FA](otp2-f-a.md) | [kotlin]<br>open suspend override fun [otp2FA](otp2-f-a.md)(params: &lt;Error class: unknown class&gt;) |
| [passwordResetConfirm](password-reset-confirm.md) | [kotlin]<br>open suspend override fun [passwordResetConfirm](password-reset-confirm.md)(params: [PasswordRecoveryConfirmRequestParams](../../com.trustless.requests.identity.passwordRecoveryConfirm/-password-recovery-confirm-request-params/index.md))<br>Confirm password reset |
| [registerUser](register-user.md) | [kotlin]<br>open suspend override fun [registerUser](register-user.md)(params: [RegisterUserRequestParams](../../com.trustless.requests.identity.registerUser/-register-user-request-params/index.md)): [StaqRegisterUserResponse](../../com.trustless.requests.identity/-staq-register-user-response/index.md)<br>Creates a new user of the application |
| [registerUser2FA](register-user2-f-a.md) | [kotlin]<br>open suspend override fun [registerUser2FA](register-user2-f-a.md)(params: &lt;Error class: unknown class&gt;) |
| [resetPassword](reset-password.md) | [kotlin]<br>open suspend override fun [resetPassword](reset-password.md)(params: [PasswordRecoveryRequestParams](../../com.trustless.requests.identity.passwordRecovery/-password-recovery-request-params/index.md))<br>Initiate password reset |
| [retrieveUser](retrieve-user.md) | [kotlin]<br>open suspend override fun [retrieveUser](retrieve-user.md)(): [StaqRetrieveUserResponse](../../com.trustless.requests.identity/-staq-retrieve-user-response/index.md)<br>Retrieves the details of an existing user |
| [saveUserTokenWithPasscode](save-user-token-with-passcode.md) | [kotlin]<br>open suspend override fun [saveUserTokenWithPasscode](save-user-token-with-passcode.md)(passcode: String)<br>@RequiresApi(value = 23)<br>open suspend override fun [saveUserTokenWithPasscode](save-user-token-with-passcode.md)(passcode: String, useBiometry: Boolean) |
| [send2FAOtp](send2-f-a-otp.md) | [kotlin]<br>open suspend override fun [send2FAOtp](send2-f-a-otp.md)(params: &lt;Error class: unknown class&gt;) |
| [tryExtractingSavedTokenWithBiometry](try-extracting-saved-token-with-biometry.md) | [kotlin]<br>open override fun [tryExtractingSavedTokenWithBiometry](try-extracting-saved-token-with-biometry.md)() |
| [updatePassword](update-password.md) | [kotlin]<br>open suspend override fun [updatePassword](update-password.md)(params: [ResetPasswordRequestParams](../../com.trustless.requests.identity.resetPassword/-reset-password-request-params/index.md))<br>Changes password for a user |
| [updateUser](update-user.md) | [kotlin]<br>open suspend override fun [updateUser](update-user.md)(params: [UpdateUserRequestParams](../../com.trustless.requests.identity.updateUser/-update-user-request-params/index.md)): [StaqRetrieveUserResponse](../../com.trustless.requests.identity/-staq-retrieve-user-response/index.md)<br>Updates the details of an existing user |
