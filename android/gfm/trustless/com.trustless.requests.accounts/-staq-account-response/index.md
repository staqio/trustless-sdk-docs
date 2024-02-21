//[trustless](../../../index.md)/[com.trustless.requests.accounts](../index.md)/[StaqAccountResponse](index.md)

# StaqAccountResponse

[kotlin]\
@Serializable

data class [StaqAccountResponse](index.md)

## Properties

| Name | Summary |
|---|---|
| [alternateNumber](alternate-number.md) | [kotlin]<br>@SerialName(value = &quot;AlternateNumber&quot;)<br>val [alternateNumber](alternate-number.md): String? = null<br>Alternate account number |
| [availableBalance](available-balance.md) | [kotlin]<br>@SerialName(value = &quot;AvailableBalance&quot;)<br>val [availableBalance](available-balance.md): Double<br>Account available balance in the account currency |
| [bankName](bank-name.md) | [kotlin]<br>@SerialName(value = &quot;BankName&quot;)<br>val [bankName](bank-name.md): String<br>Bank name |
| [blockedAmount](blocked-amount.md) | [kotlin]<br>@SerialName(value = &quot;BlockedAmount&quot;)<br>val [blockedAmount](blocked-amount.md): Double = 0.0<br>Account blocked amount in the account currency |
| [branch](branch.md) | [kotlin]<br>@SerialName(value = &quot;Branch&quot;)<br>val [branch](branch.md): String<br>The code of the Bank branch that holds the account |
| [currencyCode](currency-code.md) | [kotlin]<br>@SerialName(value = &quot;CurrencyCode&quot;)<br>val [currencyCode](currency-code.md): String<br>The ISO 3 chars code of the account currency |
| [currentBalance](current-balance.md) | [kotlin]<br>@SerialName(value = &quot;CurrentBalance&quot;)<br>val [currentBalance](current-balance.md): Double<br>Account current balance in the account currency |
| [customer](customer.md) | [kotlin]<br>@SerialName(value = &quot;Customer&quot;)<br>val [customer](customer.md): [StaqCustomer](../-staq-customer/index.md)<br>Customer data object |
| [dormant](dormant.md) | [kotlin]<br>@SerialName(value = &quot;Dormant&quot;)<br>val [dormant](dormant.md): Boolean<br>The indication that account is dormant |
| [iban](iban.md) | [kotlin]<br>@SerialName(value = &quot;IBAN&quot;)<br>val [iban](iban.md): String<br>Account IBAN |
| [localCurrencyCurrentBalance](local-currency-current-balance.md) | [kotlin]<br>@SerialName(value = &quot;LocalCurrencyCurrentBalance&quot;)<br>val [localCurrencyCurrentBalance](local-currency-current-balance.md): Double<br>Account current balance in JOD |
| [name](name.md) | [kotlin]<br>@SerialName(value = &quot;Name&quot;)<br>val [name](name.md): String<br>Account name |
| [noCredit](no-credit.md) | [kotlin]<br>@SerialName(value = &quot;NoCredit&quot;)<br>val [noCredit](no-credit.md): Boolean<br>The indication that account credit is prohibited |
| [noDebit](no-debit.md) | [kotlin]<br>@SerialName(value = &quot;NoDebit&quot;)<br>val [noDebit](no-debit.md): Boolean<br>The indication that account debit is prohibited |
| [number](number.md) | [kotlin]<br>@SerialName(value = &quot;Number&quot;)<br>val [number](number.md): String<br>Number |
| [swift](swift.md) | [kotlin]<br>@SerialName(value = &quot;SWIFT&quot;)<br>val [swift](swift.md): String<br>SWIFT code |
| [typeRaw](type-raw.md) | [kotlin]<br>@SerialName(value = &quot;Type&quot;)<br>val [typeRaw](type-raw.md): String |
