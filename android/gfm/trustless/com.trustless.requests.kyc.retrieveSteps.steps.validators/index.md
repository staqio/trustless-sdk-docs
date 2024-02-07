//[trustless](../../index.md)/[com.trustless.requests.kyc.retrieveSteps.steps.validators](index.md)

# Package-level declarations

## Types

| Name | Summary |
|---|---|
| [KycBooleanFieldValidator](-kyc-boolean-field-validator/index.md) | <br>class [KycBooleanFieldValidator](-kyc-boolean-field-validator/index.md)(validations: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[Validation](../com.trustless.requests.kyc.retrieveSteps/-validation/index.md)&gt;) : [KycFieldValidator](-kyc-field-validator/index.md)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt; |
| [KycDateFieldValidator](-kyc-date-field-validator/index.md) | <br>class [KycDateFieldValidator](-kyc-date-field-validator/index.md)(validations: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[Validation](../com.trustless.requests.kyc.retrieveSteps/-validation/index.md)&gt;) : [KycFieldValidator](-kyc-field-validator/index.md)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt; |
| [KycDefaultStringValidator](-kyc-default-string-validator/index.md) | <br>class [KycDefaultStringValidator](-kyc-default-string-validator/index.md)(validations: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[Validation](../com.trustless.requests.kyc.retrieveSteps/-validation/index.md)&gt;) : [KycFieldValidator](-kyc-field-validator/index.md)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt; |
| [KycFieldValidator](-kyc-field-validator/index.md) | <br>interface [KycFieldValidator](-kyc-field-validator/index.md)&lt;[T](-kyc-field-validator/index.md)&gt; |
| [StringFieldValidatorManager](-string-field-validator-manager/index.md) | <br>class [StringFieldValidatorManager](-string-field-validator-manager/index.md)(field: [Field](../com.trustless.requests.kyc.retrieveSteps/-field/index.md), validator: [KycFieldValidator](-kyc-field-validator/index.md)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt; = KycDefaultStringValidator(field.validations)) |

## Functions

| Name | Summary |
|---|---|
| [filterValidate](filter-validate.md) | <br>fun [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[Validation](../com.trustless.requests.kyc.retrieveSteps/-validation/index.md)&gt;.[filterValidate](filter-validate.md)(isValid: (it: [Validation](../com.trustless.requests.kyc.retrieveSteps/-validation/index.md)) -&gt; [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[FieldError](../com.trustless.requests.kyc.retrieveSteps.steps.fields/-field-error/index.md)&gt; |
