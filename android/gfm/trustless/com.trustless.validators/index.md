//[trustless](../../index.md)/[com.trustless.validators](index.md)

# Package-level declarations

## Functions

| Name | Summary |
|---|---|
| [isAccountNameValid](is-account-name-valid.md) | [kotlin]<br>fun [isAccountNameValid](is-account-name-valid.md)(name: String): Boolean<br>Checks if Account name is within a valid range 1, 105 |
| [isAmountValid](is-amount-valid.md) | [kotlin]<br>fun [isAmountValid](is-amount-valid.md)(amount: Double): Boolean<br>Validates if the amount is within the range of 0.0001 to 1.0E18 (inclusive), allowing for a wide range of valid monetary values. |
| [isCardHolderNameValid](is-card-holder-name-valid.md) | [kotlin]<br>fun [isCardHolderNameValid](is-card-holder-name-valid.md)(name: String): Boolean<br>Checks if the card holder's name length is less than or equal to 22 characters, and if it matches the regex pattern ^(A-Z'.-+\s?)+$ which allows uppercase letters, apostrophes, periods, hyphens, and spaces. |
| [isCodeValid](is-code-valid.md) | [kotlin]<br>fun [isCodeValid](is-code-valid.md)(code: String): Boolean<br>Verifies if a code is valid by ensuring it is exactly 20 characters long. This could be used for validation of fixed-length identifiers or security tokens. |
| [isCurrencyCodeValid](is-currency-code-valid.md) | [kotlin]<br>fun [isCurrencyCodeValid](is-currency-code-valid.md)(code: String): Boolean<br>Checks if currency code matches regex A-Z{3} |
| [isEmailValid](is-email-valid.md) | [kotlin]<br>fun [isEmailValid](is-email-valid.md)(email: String): Boolean<br>Validates an email address by checking if its length is between 3 and 255 characters. This range covers most valid email addresses without specifying the exact format. |
| [isLimitValid](is-limit-valid.md) | [kotlin]<br>fun [isLimitValid](is-limit-valid.md)(limit: Double): Boolean<br>Checks if the limit is valid by ensuring it does not exceed 1 trillion (1,000,000,000,000). This function is useful for setting maximum allowable credit limits or similar financial thresholds. |
| [isMobileNumberValid](is-mobile-number-valid.md) | [kotlin]<br>fun [isMobileNumberValid](is-mobile-number-valid.md)(mobile: String): Boolean<br>Checks if the card holder's name length is less than or equal to 22 characters, and if it matches the regex pattern ^(A-Z'.-+\s?)+$ which allows uppercase letters, apostrophes, periods, hyphens, and spaces. |
| [isMonthValid](is-month-valid.md) | [kotlin]<br>fun [isMonthValid](is-month-valid.md)(month: Int): Boolean<br>Validates a month by ensuring it is an integer within the range of 1 to 12, corresponding to the 12 months in a year. This function is useful for date validation tasks requiring a valid month value. |
| [isNameValid](is-name-valid.md) | [kotlin]<br>fun [isNameValid](is-name-valid.md)(name: String): Boolean<br>Validates a name by ensuring its length is between 1 and 255 characters. This broad range allows for most personal, full, or even company names to be considered valid without imposing strict constraints on format or characters. |
| [isPageNumberValid](is-page-number-valid.md) | [kotlin]<br>fun [isPageNumberValid](is-page-number-valid.md)(pageSize: Int): Boolean<br>Checks if pageNumber is within a valid range 1, 4000000 |
| [isPageSizeValid](is-page-size-valid.md) | [kotlin]<br>fun [isPageSizeValid](is-page-size-valid.md)(pageSize: Int): Boolean<br>Checks if pageSize is within a valid range 10, 500 |
| [isPasswordValid](is-password-valid.md) | [kotlin]<br>fun [isPasswordValid](is-password-valid.md)(password: String): Boolean<br>Validates a password by ensuring its length is between 8 and 255 characters. This validation allows for a broad range of password complexities to accommodate various security requirements. |
| [isPhoneNumberValid](is-phone-number-valid.md) | [kotlin]<br>fun [isPhoneNumberValid](is-phone-number-valid.md)(number: String): Boolean<br>Validates a phone number by checking if its length is between 4 and 16 characters and if it matches the regex pattern ^\\+0-9*$, which requires the number to start with a '+' followed by a non-zero digit and then any sequence of digits, ensuring it is an international format. |
| [validateAccountName](validate-account-name.md) | [kotlin]<br>fun [validateAccountName](validate-account-name.md)(name: String)<br>Validates an account name. |
| [validateAmount](validate-amount.md) | [kotlin]<br>fun [validateAmount](validate-amount.md)(amount: Double)<br>Validates a monetary amount and throws TrustlessAmountException if the amount does not meet the validation criteria. |
| [validateCardHolderName](validate-card-holder-name.md) | [kotlin]<br>fun [validateCardHolderName](validate-card-holder-name.md)(name: String)<br>Validates a cardholder's name and throws TrustlessCardholderNameException if the name does not meet the validation criteria. |
| [validateCode](validate-code.md) | [kotlin]<br>fun [validateCode](validate-code.md)(code: String)<br>Validates a code throws TrustlessCodeException if the code does not meet the validation criteria. |
| [validateCurrencyCode](validate-currency-code.md) | [kotlin]<br>fun [validateCurrencyCode](validate-currency-code.md)(code: String)<br>Validates a currency code. |
| [validateEmail](validate-email.md) | [kotlin]<br>fun [validateEmail](validate-email.md)(email: String)<br>Validates an email and throws TrustlessEmailException if the email does not meet the validation criteria. |
| [validateLimit](validate-limit.md) | [kotlin]<br>fun [validateLimit](validate-limit.md)(limit: Double)<br>Validates a financial limit and throws TrustlessLimitException if the limit does not meet the validation criteria. |
| [validateMobileNumber](validate-mobile-number.md) | [kotlin]<br>fun [validateMobileNumber](validate-mobile-number.md)(mobile: String)<br>Validates a mobile number. |
| [validateMonth](validate-month.md) | [kotlin]<br>fun [validateMonth](validate-month.md)(month: Int)<br>Throws a TrustlessMonthException if the provided month integer is not valid. This function utilizes isMonthValid to check the month's validity and acts as a guard in contexts where an invalid month value cannot be tolerated. |
| [validateName](validate-name.md) | [kotlin]<br>fun [validateName](validate-name.md)(name: String, nameCode: String)<br>Validates a name and throws TrustlessInvalidNameException |
| [validatePageNumber](validate-page-number.md) | [kotlin]<br>fun [validatePageNumber](validate-page-number.md)(pageNumber: Int)<br>Validates a page number for pagination purposes. |
| [validatePageSize](validate-page-size.md) | [kotlin]<br>fun [validatePageSize](validate-page-size.md)(pageSize: Int)<br>Validates a page size for pagination purposes. |
| [validatePassword](validate-password.md) | [kotlin]<br>fun [validatePassword](validate-password.md)(password: String)<br>Validates a password and throws TrustlessPasswordException if the password does not meet the validation criteria. |
| [validatePhoneNumber](validate-phone-number.md) | [kotlin]<br>fun [validatePhoneNumber](validate-phone-number.md)(number: String)<br>Validates a phone number and throws TrustlessPhoneNumberException if the number does not meet the validation criteria. |
