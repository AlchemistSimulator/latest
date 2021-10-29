//[alchemist](../../../../index.md)/[it.unibo.alchemist.model.cognitiveagents.impact.individual](../../index.md)/[HelpAttitudeSpec](../index.md)/[ElderlyMale](index.md)

# ElderlyMale

[jvm]\
object [ElderlyMale](index.md) : ConfigSpec

Elderly males attitudes.

## Functions

| Name | Summary |
|---|---|
| [addInnerSpec](../../-speed-spec/index.md#1157218497%2FFunctions%2F-267951372) | [jvm]<br>open override fun [addInnerSpec](../../-speed-spec/index.md#1157218497%2FFunctions%2F-267951372)(spec: Spec) |
| [addItem](../../-speed-spec/index.md#-1176720725%2FFunctions%2F-267951372) | [jvm]<br>open override fun [addItem](../../-speed-spec/index.md#-1176720725%2FFunctions%2F-267951372)(item: Item<*>) |
| [get](../../-speed-spec/index.md#216658617%2FFunctions%2F-267951372) | [jvm]<br>open operator fun [get](../../-speed-spec/index.md#216658617%2FFunctions%2F-267951372)(path: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): Spec |
| [lazy](../../-speed-spec/index.md#-57241479%2FFunctions%2F-267951372) | [jvm]<br>inline fun <[T](../../-speed-spec/index.md#-57241479%2FFunctions%2F-267951372)> [lazy](../../-speed-spec/index.md#-57241479%2FFunctions%2F-267951372)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, description: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), noinline thunk: (config: ItemContainer) -> [T](../../-speed-spec/index.md#-57241479%2FFunctions%2F-267951372)): LazyProperty<[T](../../-speed-spec/index.md#-57241479%2FFunctions%2F-267951372)> |
| [optional](../../-speed-spec/index.md#-1307546368%2FFunctions%2F-267951372) | [jvm]<br>inline fun <[T](../../-speed-spec/index.md#-1307546368%2FFunctions%2F-267951372)> [optional](../../-speed-spec/index.md#-1307546368%2FFunctions%2F-267951372)(default: [T](../../-speed-spec/index.md#-1307546368%2FFunctions%2F-267951372), name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, description: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): OptionalProperty<[T](../../-speed-spec/index.md#-1307546368%2FFunctions%2F-267951372)> |
| [plus](../../-speed-spec/index.md#-1897999851%2FFunctions%2F-267951372) | [jvm]<br>open operator fun [plus](../../-speed-spec/index.md#-1897999851%2FFunctions%2F-267951372)(spec: Spec): Spec |
| [qualify](../../-speed-spec/index.md#-620175742%2FFunctions%2F-267951372) | [jvm]<br>open fun [qualify](../../-speed-spec/index.md#-620175742%2FFunctions%2F-267951372)(item: Item<*>): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [required](../../-speed-spec/index.md#1352156512%2FFunctions%2F-267951372) | [jvm]<br>inline fun <[T](../../-speed-spec/index.md#1352156512%2FFunctions%2F-267951372)> [required](../../-speed-spec/index.md#1352156512%2FFunctions%2F-267951372)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, description: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): RequiredProperty<[T](../../-speed-spec/index.md#1352156512%2FFunctions%2F-267951372)> |
| [withFallback](../../-speed-spec/index.md#73507879%2FFunctions%2F-267951372) | [jvm]<br>open fun [withFallback](../../-speed-spec/index.md#73507879%2FFunctions%2F-267951372)(spec: Spec): Spec |
| [withPrefix](../../-speed-spec/index.md#-1060748701%2FFunctions%2F-267951372) | [jvm]<br>open fun [withPrefix](../../-speed-spec/index.md#-1060748701%2FFunctions%2F-267951372)(prefix: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): Spec |

## Properties

| Name | Summary |
|---|---|
| [adultFemale](adult-female.md) | [jvm]<br>val [adultFemale](adult-female.md): RequiredItem<[Pair](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)>><br>The attitude of an elderly male to help an adult female. |
| [adultMale](adult-male.md) | [jvm]<br>val [adultMale](adult-male.md): RequiredItem<[Pair](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)>><br>The attitude of an elderly male to help a male adult. |
| [childFemale](child-female.md) | [jvm]<br>val [childFemale](child-female.md): RequiredItem<[Pair](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)>><br>The attitude of an elderly male to help a female child. |
| [childMale](child-male.md) | [jvm]<br>val [childMale](child-male.md): RequiredItem<[Pair](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)>><br>The attitude of an elderly male to help a male child. |
| [elderlyFemale](elderly-female.md) | [jvm]<br>val [elderlyFemale](elderly-female.md): RequiredItem<[Pair](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)>><br>The attitude of an elderly male to help an elderly woman. |
| [elderlyMale](elderly-male.md) | [jvm]<br>val [elderlyMale](elderly-male.md): RequiredItem<[Pair](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)>><br>The attitude of an elderly male to help a male elderly. |
| [innerSpecs](index.md#-212783855%2FProperties%2F-267951372) | [jvm]<br>open override val [innerSpecs](index.md#-212783855%2FProperties%2F-267951372): [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<Spec> |
| [items](index.md#1108091847%2FProperties%2F-267951372) | [jvm]<br>open override val [items](index.md#1108091847%2FProperties%2F-267951372): [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<Item<*>> |
| [prefix](index.md#607412961%2FProperties%2F-267951372) | [jvm]<br>override val [prefix](index.md#607412961%2FProperties%2F-267951372): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
