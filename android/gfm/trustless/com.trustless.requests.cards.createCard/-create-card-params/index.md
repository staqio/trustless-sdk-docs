//[trustless](../../../index.md)/[com.trustless.requests.cards.createCard](../index.md)/[CreateCardParams](index.md)

# CreateCardParams

class [CreateCardParams](index.md) : [JSONParamsBuilder](../../com.trustless.params/-j-s-o-n-params-builder/index.md)

[Server Api Reference](https://developer.staq.io/docs/apis/cards#/Cards/Create%20card.%20V2)

#### Parameters

kotlin

| | |
|---|---|
| currency | ISO3 Currency code for the card (e.g &quot;JOD&quot;, &quot;USD&quot;, &quot;EUR&quot;). Pattern ^A-Z{3}$ |
| mobileNumber | Cardholder's mobile number (conditional). Should start from a single 0 (zero), no + (plus) sign is allowed. The card creation process is configured (upon your request) with automatic card 3DS enrollment. MAXLENGTH: 15 MINLENGTH: 4 PATTERN: ^0?1-9+0-9*$ |
| cardHolderName | Card holder name (optional) MAXLENGTH: 22 PATTERN: ^(A-Z'.-+\s?)+$ |
| creditDetails | Object with class details. |

## Types

| Name | Summary |
|---|---|
| [Builder](-builder/index.md) | [kotlin]<br>class [Builder](-builder/index.md)(currency: String)<br>Builder to initiate [CreateCardParams](index.md) |
