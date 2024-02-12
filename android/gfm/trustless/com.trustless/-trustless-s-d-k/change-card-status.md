//[trustless](../../../index.md)/[com.trustless](../index.md)/[TrustlessSDK](index.md)/[changeCardStatus](change-card-status.md)

# changeCardStatus

[kotlin]\
suspend fun [changeCardStatus](change-card-status.md)(token: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), status: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [StaqChangeCardStatusResponse](../../com.trustless.requests.cards/-staq-change-card-status-response/index.md)

The method allows managing the card status

[Server Api Reference](https://developer.staq.io/docs/apis/cards#/Cards/Set%20status)

#### Parameters

kotlin

| | |
|---|---|
| token | The token of the card returned when card was issued |
| status | Status to be assigned to the card ENUM:  ACTIVATED, FROZEN, CLOSED |
