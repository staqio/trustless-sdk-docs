//[trustless](../../../index.md)/[com.trustless.providers.implementations](../index.md)/[SimulationProviderImp](index.md)/[setAccountBalance](set-account-balance.md)

# setAccountBalance

[kotlin]\
open override fun [setAccountBalance](set-account-balance.md)(accountNumber: String): [SetBalanceRequest](../../com.trustless.requests.simulate.setBalance/-set-balance-request/index.md)

Set Account Balance (DEV ONLY)

#### Return

[SetBalanceRequest](../../com.trustless.requests.simulate.setBalance/-set-balance-request/index.md) request class to handle request.

#### Parameters

kotlin

| | |
|---|---|
| accountNumber | Bank account number of the customer |

#### Throws

| | |
|---|---|
| [TrustlessException](../../com.trustless.exceptions/-trustless-exception/index.md) | Is thrown when the server returns custom error, or when error was not expected by the SDK |
| [TrustlessAppTokenException](../../com.trustless.exceptions/-trustless-app-token-exception/index.md) | Is thrown when the token expires, either due to time period or server forced expiration |
| [TrustlessMalformedResponse](../../com.trustless.exceptions/-trustless-malformed-response/index.md) | Is thrown when server returned unexpected format of the data |
| [TrustlessExceptionListener](../../com.trustless.exceptions/-trustless-exception-listener/index.md) | Is thrown when developer has not set security listener |
| [TrustlessExceptionSecurityProviderIsNotInstalled](../../com.trustless.exceptions/-trustless-exception-security-provider-is-not-installed/index.md) | Is thrown when user's device doesn't have a security provider |
| CancellationException | Is thrown usually when the developer cancels the coroutine |
| [TrustlessNotInitializedSdkException](../../com.trustless.exceptions/-trustless-not-initialized-sdk-exception/index.md) | Is thrown when trying to access this method while sdk is not initialized |
