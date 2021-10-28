//[alchemist](../../../index.md)/[it.unibo.alchemist.model.cognitiveagents.impact.individual](../index.md)/[SpeedSpec](index.md)

# SpeedSpec

[jvm]\
object [SpeedSpec](index.md) : ConfigSpec

A specification of the parameters regarding speeds to load from a config file.

## Functions

| Name | Summary |
|---|---|
| [addInnerSpec](index.md#1157218497%2FFunctions%2F-267951372) | [jvm]<br>open override fun [addInnerSpec](index.md#1157218497%2FFunctions%2F-267951372)(spec: Spec) |
| [addItem](index.md#-1176720725%2FFunctions%2F-267951372) | [jvm]<br>open override fun [addItem](index.md#-1176720725%2FFunctions%2F-267951372)(item: Item<*>) |
| [get](index.md#216658617%2FFunctions%2F-267951372) | [jvm]<br>open operator fun [get](index.md#216658617%2FFunctions%2F-267951372)(path: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): Spec |
| [lazy](index.md#-57241479%2FFunctions%2F-267951372) | [jvm]<br>inline fun <[T](index.md#-57241479%2FFunctions%2F-267951372)> [lazy](index.md#-57241479%2FFunctions%2F-267951372)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, description: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), noinline thunk: (config: ItemContainer) -> [T](index.md#-57241479%2FFunctions%2F-267951372)): LazyProperty<[T](index.md#-57241479%2FFunctions%2F-267951372)> |
| [optional](index.md#-1307546368%2FFunctions%2F-267951372) | [jvm]<br>inline fun <[T](index.md#-1307546368%2FFunctions%2F-267951372)> [optional](index.md#-1307546368%2FFunctions%2F-267951372)(default: [T](index.md#-1307546368%2FFunctions%2F-267951372), name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, description: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): OptionalProperty<[T](index.md#-1307546368%2FFunctions%2F-267951372)> |
| [plus](index.md#-1897999851%2FFunctions%2F-267951372) | [jvm]<br>open operator fun [plus](index.md#-1897999851%2FFunctions%2F-267951372)(spec: Spec): Spec |
| [qualify](index.md#-620175742%2FFunctions%2F-267951372) | [jvm]<br>open fun [qualify](index.md#-620175742%2FFunctions%2F-267951372)(item: Item<*>): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [required](index.md#1352156512%2FFunctions%2F-267951372) | [jvm]<br>inline fun <[T](index.md#1352156512%2FFunctions%2F-267951372)> [required](index.md#1352156512%2FFunctions%2F-267951372)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, description: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): RequiredProperty<[T](index.md#1352156512%2FFunctions%2F-267951372)> |
| [withFallback](index.md#73507879%2FFunctions%2F-267951372) | [jvm]<br>open fun [withFallback](index.md#73507879%2FFunctions%2F-267951372)(spec: Spec): Spec |
| [withPrefix](index.md#-1060748701%2FFunctions%2F-267951372) | [jvm]<br>open fun [withPrefix](index.md#-1060748701%2FFunctions%2F-267951372)(prefix: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): Spec |

## Properties

| Name | Summary |
|---|---|
| [adultFemale](adult-female.md) | [jvm]<br>val [adultFemale](adult-female.md): RequiredItem<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)> |
| [adultMale](adult-male.md) | [jvm]<br>val [adultMale](adult-male.md): RequiredItem<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)> |
| [childFemale](child-female.md) | [jvm]<br>val [childFemale](child-female.md): RequiredItem<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)> |
| [childMale](child-male.md) | [jvm]<br>val [childMale](child-male.md): RequiredItem<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)> |
| [default](default.md) | [jvm]<br>val [default](default.md): RequiredItem<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)> |
| [elderlyFemale](elderly-female.md) | [jvm]<br>val [elderlyFemale](elderly-female.md): RequiredItem<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)> |
| [elderlyMale](elderly-male.md) | [jvm]<br>val [elderlyMale](elderly-male.md): RequiredItem<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)> |
| [innerSpecs](index.md#-853171611%2FProperties%2F-267951372) | [jvm]<br>open override val [innerSpecs](index.md#-853171611%2FProperties%2F-267951372): [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<Spec> |
| [items](index.md#1932569075%2FProperties%2F-267951372) | [jvm]<br>open override val [items](index.md#1932569075%2FProperties%2F-267951372): [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<Item<*>> |
| [prefix](index.md#396403253%2FProperties%2F-267951372) | [jvm]<br>override val [prefix](index.md#396403253%2FProperties%2F-267951372): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [variance](variance.md) | [jvm]<br>val [variance](variance.md): RequiredItem<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)> |
