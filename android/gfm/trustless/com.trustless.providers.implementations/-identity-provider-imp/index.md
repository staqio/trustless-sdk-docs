//[trustless](../../../index.md)/[com.trustless.providers.implementations](../index.md)/[IdentityProviderImp](index.md)

# IdentityProviderImp

[kotlin]\
class [IdentityProviderImp](index.md) : [IdentityProvider](../../com.trustless.providers/-identity-provider/index.md)

## Functions

| Name | Summary |
|---|---|
| [login](login.md) | [kotlin]<br>open suspend override fun [login](login.md)(params: [UserTokenRequestParams](../../com.trustless.requests.identity.userToken/-user-token-request-params/index.md), useBiometry: Boolean): [StaqUserTokenResponse](../../com.trustless.requests.identity/-staq-user-token-response/index.md)<br>Returns access token for an application or user |
| [logout](logout.md) | [kotlin]<br>open suspend override fun [logout](logout.md)()<br>This endpoint is used to invalidate the token, and to remove the data of the current user from the memory. Refer to the Advanced section about deinitialization for more details |
| [passwordResetConfirm](password-reset-confirm.md) | [kotlin]<br>open suspend override fun [passwordResetConfirm](password-reset-confirm.md)(params: [PasswordRecoveryConfirmRequestParams](../../com.trustless.requests.identity.passwordRecoveryConfirm/-password-recovery-confirm-request-params/index.md))<br>Confirm password reset |
| [registerUser](register-user.md) | [kotlin]<br>open suspend override fun [registerUser](register-user.md)(params: [RegisterUserRequestParams](../../com.trustless.requests.identity.registerUser/-register-user-request-params/index.md)): [StaqRegisterUserResponse](../../com.trustless.requests.identity/-staq-register-user-response/index.md)<br>Creates a new user of the application |
| [resetPassword](reset-password.md) | [kotlin]<br>open suspend override fun [resetPassword](reset-password.md)(params: [PasswordRecoveryRequestParams](../../com.trustless.requests.identity.passwordRecovery/-password-recovery-request-params/index.md))<br>Initiate password reset |
| [retrieveUser](retrieve-user.md) | [kotlin]<br>open suspend override fun [retrieveUser](retrieve-user.md)(): [StaqRetrieveUserResponse](../../com.trustless.requests.identity/-staq-retrieve-user-response/index.md)<br>Retrieves the details of an existing user |
| [updatePassword](update-password.md) | [kotlin]<br>open suspend override fun [updatePassword](update-password.md)(params: [ResetPasswordRequestParams](../../com.trustless.requests.identity.resetPassword/-reset-password-request-params/index.md))<br>Changes password for a user |
| [updateUser](update-user.md) | [kotlin]<br>open suspend override fun [updateUser](update-user.md)(params: [UpdateUserRequestParams](../../com.trustless.requests.identity.updateUser/-update-user-request-params/index.md)): [StaqRetrieveUserResponse](../../com.trustless.requests.identity/-staq-retrieve-user-response/index.md)<br>Updates the details of an existing user |
