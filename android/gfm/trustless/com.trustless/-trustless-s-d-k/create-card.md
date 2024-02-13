//[trustless](../../../index.md)/[com.trustless](../index.md)/[TrustlessSDK](index.md)/[createCard](create-card.md)

# createCard

[kotlin]\
suspend fun [createCard](create-card.md)(params: [CreateCardParams](../../com.trustless.requests.cards.createCard/-create-card-params/index.md)): [StaqCardDetails](../../com.trustless.requests.cards/-staq-card-details/index.md)

Creates a new virtual prepaid card. After card is created, you can retrieve sensitive card information (e.g. Pan. Cvv) later using /pan API endpoint.

[Server Api Reference](https://developer.staq.io/docs/apis/cards#/Cards/Create%20card.%20V2)

#### Parameters

kotlin

| | |
|---|---|
| params | params to create a card |

#### Throws

| | |
|---|---|
| [TrustlessException](../../com.trustless.exceptions/-trustless-exception/index.md) | Is thrown when the server returns custom error, or when error was not expected by the SDK |
| [TrustlessUserTokenExpiredException](../../com.trustless.exceptions/-trustless-user-token-expired-exception/index.md) | Is thrown when the token expires, either due to time period or server forced expiration |
| [TrustlessMalformedResponse](../../com.trustless.exceptions/-trustless-malformed-response/index.md) | Is thrown when server returned unexpected format of the data |
| CancellationException | Is thrown usually when the developer cancels the coroutine |
