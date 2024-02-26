//[trustless](../../../../index.md)/[com.trustless](../../index.md)/[TrustlessSDK](../index.md)/[Companion](index.md)

# Companion

[kotlin]\
object [Companion](index.md)

## Properties

| Name | Summary |
|---|---|
| [accountsProvider](accounts-provider.md) | [kotlin]<br>val [accountsProvider](accounts-provider.md): [AccountsProvider](../../../com.trustless.providers/-accounts-provider/index.md)<br>Accounts-related operations, including creating account, getting accounts and account details, and close account. |
| [cardsProvider](cards-provider.md) | [kotlin]<br>val [cardsProvider](cards-provider.md): [CardsProvider](../../../com.trustless.providers/-cards-provider/index.md)<br>Cards-related operations, including creating card, getting card and card details, close card. |
| [cliqProvider](cliq-provider.md) | [kotlin]<br>val [cliqProvider](cliq-provider.md): [CliQProvider](../../../com.trustless.providers/-cli-q-provider/index.md)<br>CliQ-related operations, including getting aliases and creating alias. |
| [identityProvider](identity-provider.md) | [kotlin]<br>val [identityProvider](identity-provider.md): [IdentityProvider](../../../com.trustless.providers/-identity-provider/index.md)<br>Authentication-related operations, including sign-in, sign-out, and user registration. |
| [instance](instance.md) | [kotlin]<br>val [instance](instance.md): [TrustlessSDK](../index.md)<br>Provides access to the current instance of the TrustlessSDK. This instance is lazily initialized, ensuring that it is created only when needed. |
| [kycProvider](kyc-provider.md) | [kotlin]<br>val [kycProvider](kyc-provider.md): [KYCProvider](../../../com.trustless.providers/-k-y-c-provider/index.md)<br>KYC-related operations, including getting KYC steps and sending request. |
| [simulationProvider](simulation-provider.md) | [kotlin]<br>val [simulationProvider](simulation-provider.md): [SimulationProvider](../../../com.trustless.providers/-simulation-provider/index.md)<br>Simulation-related operations, including approving kyc, setting accounts balance. |
| [transfersProvider](transfers-provider.md) | [kotlin]<br>val [transfersProvider](transfers-provider.md): [TransfersProvider](../../../com.trustless.providers/-transfers-provider/index.md)<br>Transfers-related operations, including creating card, getting card and card details, close card. |

## Functions

| Name | Summary |
|---|---|
| [deinitialize](deinitialize.md) | [kotlin]<br>fun [deinitialize](deinitialize.md)()<br>Cleans up the SDK's allocated resources and resets its state. This function should be called when the SDK is no longer needed, typically at the application's shutdown. |
| [initialize](initialize.md) | [kotlin]<br>fun [initialize](initialize.md)(configuration: [TrustlessConfiguration](../../../com.trustless.requests.utils/-trustless-configuration/index.md), context: Context)<br>Initializes the TrustlessSDK with the provided configuration and application context. This step is essential for the SDK to function correctly. Without initialization, the SDK operations will not be executed as expected. Ensure this method is called once during your application's startup, typically in your Application class or main activity's onCreate method. |
