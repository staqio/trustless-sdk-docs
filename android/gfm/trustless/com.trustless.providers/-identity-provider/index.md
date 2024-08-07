//[trustless](../../../index.md)/[com.trustless.providers](../index.md)/[IdentityProvider](index.md)

# IdentityProvider

interface [IdentityProvider](index.md)

#### Inheritors

| |
|---|
| [IdentityProviderImp](../../com.trustless.providers.implementations/-identity-provider-imp/index.md) |

## Functions

| Name | Summary |
|---|---|
| [canLoginUsingSavedToken](can-login-using-saved-token.md) | [kotlin]<br>abstract suspend fun [canLoginUsingSavedToken](can-login-using-saved-token.md)(): Boolean |
| [canLoginUsingSavedTokenUsingBiometry](can-login-using-saved-token-using-biometry.md) | [kotlin]<br>abstract fun [canLoginUsingSavedTokenUsingBiometry](can-login-using-saved-token-using-biometry.md)(): Boolean |
| [clearPasscodeAndBiometry](clear-passcode-and-biometry.md) | [kotlin]<br>abstract fun [clearPasscodeAndBiometry](clear-passcode-and-biometry.md)() |
| [extractSavedToken](extract-saved-token.md) | [kotlin]<br>abstract suspend fun [extractSavedToken](extract-saved-token.md)(passcode: String) |
| [isPasscodeCorrect](is-passcode-correct.md) | [kotlin]<br>abstract suspend fun [isPasscodeCorrect](is-passcode-correct.md)(passcode: String): Boolean |
| [isUserAuthenticated](is-user-authenticated.md) | [kotlin]<br>abstract fun [isUserAuthenticated](is-user-authenticated.md)(): Boolean |
| [login](login.md) | [kotlin]<br>abstract suspend fun [login](login.md)(params: [UserTokenRequestParams](../../com.trustless.requests.identity.userToken/-user-token-request-params/index.md), useBiometry: Boolean): [StaqUserTokenResponse](../../com.trustless.requests.identity/-staq-user-token-response/index.md)<br>Returns access token for an application or user |
| [login2FA](login2-f-a.md) | [kotlin]<br>abstract suspend fun [login2FA](login2-f-a.md)(params: [UserToken2FACompleteRequestParams](../../com.trustless.requests.identity.login2FA/-user-token2-f-a-complete-request-params/index.md)): [StaqUserTokenResponse](../../com.trustless.requests.identity/-staq-user-token-response/index.md) |
| [logout](logout.md) | [kotlin]<br>abstract suspend fun [logout](logout.md)()<br>This endpoint is used to invalidate the token, and to remove the data of the current user from the memory. Refer to the Advanced section about deinitialization for more details |
| [otp2FA](otp2-f-a.md) | [kotlin]<br>abstract suspend fun [otp2FA](otp2-f-a.md)(params: [UserTokenOtp2FARequestParams](../../com.trustless.requests.identity.login2FA/-user-token-otp2-f-a-request-params/index.md)) |
| [passwordResetConfirm](password-reset-confirm.md) | [kotlin]<br>abstract suspend fun [passwordResetConfirm](password-reset-confirm.md)(params: [PasswordRecoveryConfirmRequestParams](../../com.trustless.requests.identity.passwordRecoveryConfirm/-password-recovery-confirm-request-params/index.md))<br>Confirm password reset |
| [registerUser](register-user.md) | [kotlin]<br>abstract suspend fun [registerUser](register-user.md)(params: [RegisterUserRequestParams](../../com.trustless.requests.identity.registerUser/-register-user-request-params/index.md)): [StaqRegisterUserResponse](../../com.trustless.requests.identity/-staq-register-user-response/index.md)<br>Creates a new user of the application |
| [registerUser2FA](register-user2-f-a.md) | [kotlin]<br>abstract suspend fun [registerUser2FA](register-user2-f-a.md)(params: [RegisterUserRequest2FAParams](../../com.trustless.requests.identity.registerUser/-register-user-request2-f-a-params/index.md)) |
| [resetPassword](reset-password.md) | [kotlin]<br>abstract suspend fun [resetPassword](reset-password.md)(params: [PasswordRecoveryRequestParams](../../com.trustless.requests.identity.passwordRecovery/-password-recovery-request-params/index.md))<br>Initiate password reset |
| [retrieveUser](retrieve-user.md) | [kotlin]<br>abstract suspend fun [retrieveUser](retrieve-user.md)(): [StaqRetrieveUserResponse](../../com.trustless.requests.identity/-staq-retrieve-user-response/index.md)<br>Retrieves the details of an existing user |
| [saveUserTokenWithPasscode](save-user-token-with-passcode.md) | [kotlin]<br>abstract suspend fun [saveUserTokenWithPasscode](save-user-token-with-passcode.md)(passcode: String)<br>@RequiresApi(value = 23)<br>abstract suspend fun [saveUserTokenWithPasscode](save-user-token-with-passcode.md)(passcode: String, useBiometry: Boolean) |
| [send2FAOtp](send2-f-a-otp.md) | [kotlin]<br>abstract suspend fun [send2FAOtp](send2-f-a-otp.md)(params: [Send2FAOtpRequestParams](../../com.trustless.requests.identity.login2FA/-send2-f-a-otp-request-params/index.md)) |
| [tryExtractingSavedTokenWithBiometry](try-extracting-saved-token-with-biometry.md) | [kotlin]<br>abstract fun [tryExtractingSavedTokenWithBiometry](try-extracting-saved-token-with-biometry.md)() |
| [updatePassword](update-password.md) | [kotlin]<br>abstract suspend fun [updatePassword](update-password.md)(params: [ResetPasswordRequestParams](../../com.trustless.requests.identity.resetPassword/-reset-password-request-params/index.md))<br>Changes password for a user |
| [updateUser](update-user.md) | [kotlin]<br>abstract suspend fun [updateUser](update-user.md)(params: [UpdateUserRequestParams](../../com.trustless.requests.identity.updateUser/-update-user-request-params/index.md)): [StaqRetrieveUserResponse](../../com.trustless.requests.identity/-staq-retrieve-user-response/index.md)<br>Updates the details of an existing user |
