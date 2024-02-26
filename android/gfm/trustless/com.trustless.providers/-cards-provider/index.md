//[trustless](../../../index.md)/[com.trustless.providers](../index.md)/[CardsProvider](index.md)

# CardsProvider

[kotlin]\
class [CardsProvider](index.md)

## Functions

| Name | Summary |
|---|---|
| [changeCardMobileNumber](change-card-mobile-number.md) | [kotlin]<br>suspend fun [changeCardMobileNumber](change-card-mobile-number.md)(token: String, mobile: String): [StaqChangeMobileNumberResponse](../../com.trustless.requests.cards/-staq-change-mobile-number-response/index.md)<br>Updates mobile phone number for 3DS |
| [changeCardStatus](change-card-status.md) | [kotlin]<br>suspend fun [changeCardStatus](change-card-status.md)(token: String, status: String): [StaqChangeCardStatusResponse](../../com.trustless.requests.cards/-staq-change-card-status-response/index.md)<br>The method allows managing the card status |
| [createCard](create-card.md) | [kotlin]<br>suspend fun [createCard](create-card.md)(params: [CreateCardParams](../../com.trustless.requests.cards.createCard/-create-card-params/index.md)): [StaqCardDetails](../../com.trustless.requests.cards/-staq-card-details/index.md)<br>Creates a new virtual prepaid card. After card is created, you can retrieve sensitive card information (e.g. Pan. Cvv) later using /pan API endpoint. |
| [getActiveCards](get-active-cards.md) | [kotlin]<br>suspend fun [getActiveCards](get-active-cards.md)(): List&lt;[StaqCardDetails](../../com.trustless.requests.cards/-staq-card-details/index.md)&gt;<br>Retrieves all customer's active cards with no pagination, all of the active cards are returned on one page. |
| [getBalances](get-balances.md) | [kotlin]<br>suspend fun [getBalances](get-balances.md)(token: String): List&lt;[StaqCardBalance](../../com.trustless.requests.cards/-staq-card-balance/index.md)&gt;<br>Retrieves a card balance |
| [getCardByToken](get-card-by-token.md) | [kotlin]<br>suspend fun [getCardByToken](get-card-by-token.md)(token: String): [StaqCardDetails](../../com.trustless.requests.cards/-staq-card-details/index.md)<br>Retrieves a card detailed information |
| [getCards](get-cards.md) | [kotlin]<br>fun [getCards](get-cards.md)(pageSize: Int, currentPage: Int = 1): [Paginator](../../com.trustless.paginator/-paginator/index.md)&lt;[StaqCardDetails](../../com.trustless.requests.cards/-staq-card-details/index.md)&gt;<br>Creates a new virtual prepaid card. Afer card is created, you can retrieve sensitive card information (e.g. Pan. Cvv) later using /pan API endpoint. |
| [getCardTransactions](get-card-transactions.md) | [kotlin]<br>suspend fun [getCardTransactions](get-card-transactions.md)(token: String, dateFrom: Date, dateTo: Date = Date()): List&lt;[StaqCardTransaction](../../com.trustless.requests.cards/-staq-card-transaction/index.md)&gt;<br>Retrieves all transactions for the card |
| [getCVVByToken](get-c-v-v-by-token.md) | [kotlin]<br>suspend fun [getCVVByToken](get-c-v-v-by-token.md)(token: String): [StaqGetCVVResponse](../../com.trustless.requests.cards/-staq-get-c-v-v-response/index.md)<br>Retrieves unmasked card PAN and CVV code |
| [getLimits](get-limits.md) | [kotlin]<br>suspend fun [getLimits](get-limits.md)(token: String): [StaqGetLimitResponse](../../com.trustless.requests.cards/-staq-get-limit-response/index.md)<br>Retrieves all card spending limits |
| [getPanByToken](get-pan-by-token.md) | [kotlin]<br>suspend fun [getPanByToken](get-pan-by-token.md)(token: String): [StaqGetPanResponse](../../com.trustless.requests.cards/-staq-get-pan-response/index.md)<br>Retrieves unmasked card PAN |
| [getTopUpCardRequest](get-top-up-card-request.md) | [kotlin]<br>fun [getTopUpCardRequest](get-top-up-card-request.md)(token: String): [TopUpCardRequest](../../com.trustless.requests.cards.topUp/-top-up-card-request/index.md)<br>Credits funds to a card from the customer's account |
| [getWithdrawFromCardRequest](get-withdraw-from-card-request.md) | [kotlin]<br>fun [getWithdrawFromCardRequest](get-withdraw-from-card-request.md)(token: String): [WithdrawFromCardRequest](../../com.trustless.requests.cards.withdraw/-withdraw-from-card-request/index.md)<br>Debit funds from a card to the customer's account |
| [setLimits](set-limits.md) | [kotlin]<br>suspend fun [setLimits](set-limits.md)(token: String, params: [SetLimitsParams](../../com.trustless.requests.cards.setLimits/-set-limits-params/index.md)): List&lt;[StaqSetLimitResponse](../../com.trustless.requests.cards/-staq-set-limit-response/index.md)&gt;<br>Sets a card spending limits |
