//[trustless](../../../index.md)/[com.trustless.requests.kyc.retrieveSteps](../index.md)/[RetrieveStep](index.md)

# RetrieveStep

\
@Serializable

data class [RetrieveStep](index.md)(val Id: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), val Title: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val Code: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val Missing: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), val Fields: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [FieldState](../-field-state/index.md)&gt;&gt;, val PrevStep: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val NextStep: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))

## Constructors

| | |
|---|---|
| [RetrieveStep](-retrieve-step.md) | <br>constructor(Id: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), Title: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), Code: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), Missing: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), Fields: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [FieldState](../-field-state/index.md)&gt;&gt;, PrevStep: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), NextStep: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |

## Properties

| Name | Summary |
|---|---|
| [Code](-code.md) | <br>val [Code](-code.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [Fields](-fields.md) | <br>val [Fields](-fields.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [FieldState](../-field-state/index.md)&gt;&gt; |
| [Id](-id.md) | <br>val [Id](-id.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [Missing](-missing.md) | <br>val [Missing](-missing.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [NextStep](-next-step.md) | <br>val [NextStep](-next-step.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [PrevStep](-prev-step.md) | <br>val [PrevStep](-prev-step.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [Title](-title.md) | <br>val [Title](-title.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
