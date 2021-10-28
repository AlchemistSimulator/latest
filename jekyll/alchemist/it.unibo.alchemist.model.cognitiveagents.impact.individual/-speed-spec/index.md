---
title: SpeedSpec
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.cognitiveagents.impact.individual](../index.html)/[SpeedSpec](index.html)



# SpeedSpec



[jvm]\
object [SpeedSpec](index.html) : ConfigSpec

A specification of the parameters regarding speeds to load from a config file.



## Functions


| Name | Summary |
|---|---|
| [addInnerSpec](index.html#1157218497%2FFunctions%2F-134779887) | [jvm]<br>open override fun [addInnerSpec](index.html#1157218497%2FFunctions%2F-134779887)(spec: Spec) |
| [addItem](index.html#-1176720725%2FFunctions%2F-134779887) | [jvm]<br>open override fun [addItem](index.html#-1176720725%2FFunctions%2F-134779887)(item: Item<*>) |
| [get](index.html#216658617%2FFunctions%2F-134779887) | [jvm]<br>open operator fun [get](index.html#216658617%2FFunctions%2F-134779887)(path: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): Spec |
| [lazy](index.html#-57241479%2FFunctions%2F-134779887) | [jvm]<br>inline fun <[T](index.html#-57241479%2FFunctions%2F-134779887)> [lazy](index.html#-57241479%2FFunctions%2F-134779887)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, description: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), noinline thunk: (config: ItemContainer) -> [T](index.html#-57241479%2FFunctions%2F-134779887)): LazyProperty<[T](index.html#-57241479%2FFunctions%2F-134779887)> |
| [optional](index.html#-1307546368%2FFunctions%2F-134779887) | [jvm]<br>inline fun <[T](index.html#-1307546368%2FFunctions%2F-134779887)> [optional](index.html#-1307546368%2FFunctions%2F-134779887)(default: [T](index.html#-1307546368%2FFunctions%2F-134779887), name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, description: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): OptionalProperty<[T](index.html#-1307546368%2FFunctions%2F-134779887)> |
| [plus](index.html#-1897999851%2FFunctions%2F-134779887) | [jvm]<br>open operator fun [plus](index.html#-1897999851%2FFunctions%2F-134779887)(spec: Spec): Spec |
| [qualify](index.html#-620175742%2FFunctions%2F-134779887) | [jvm]<br>open fun [qualify](index.html#-620175742%2FFunctions%2F-134779887)(item: Item<*>): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [required](index.html#1352156512%2FFunctions%2F-134779887) | [jvm]<br>inline fun <[T](index.html#1352156512%2FFunctions%2F-134779887)> [required](index.html#1352156512%2FFunctions%2F-134779887)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, description: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): RequiredProperty<[T](index.html#1352156512%2FFunctions%2F-134779887)> |
| [withFallback](index.html#73507879%2FFunctions%2F-134779887) | [jvm]<br>open fun [withFallback](index.html#73507879%2FFunctions%2F-134779887)(spec: Spec): Spec |
| [withPrefix](index.html#-1060748701%2FFunctions%2F-134779887) | [jvm]<br>open fun [withPrefix](index.html#-1060748701%2FFunctions%2F-134779887)(prefix: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): Spec |


## Properties


| Name | Summary |
|---|---|
| [adultFemale](adult-female.html) | [jvm]<br>val [adultFemale](adult-female.html): RequiredItem<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)> |
| [adultMale](adult-male.html) | [jvm]<br>val [adultMale](adult-male.html): RequiredItem<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)> |
| [childFemale](child-female.html) | [jvm]<br>val [childFemale](child-female.html): RequiredItem<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)> |
| [childMale](child-male.html) | [jvm]<br>val [childMale](child-male.html): RequiredItem<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)> |
| [default](default.html) | [jvm]<br>val [default](default.html): RequiredItem<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)> |
| [elderlyFemale](elderly-female.html) | [jvm]<br>val [elderlyFemale](elderly-female.html): RequiredItem<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)> |
| [elderlyMale](elderly-male.html) | [jvm]<br>val [elderlyMale](elderly-male.html): RequiredItem<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)> |
| [innerSpecs](index.html#-853171611%2FProperties%2F-134779887) | [jvm]<br>open override val [innerSpecs](index.html#-853171611%2FProperties%2F-134779887): [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<Spec> |
| [items](index.html#1932569075%2FProperties%2F-134779887) | [jvm]<br>open override val [items](index.html#1932569075%2FProperties%2F-134779887): [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<Item<*>> |
| [prefix](index.html#396403253%2FProperties%2F-134779887) | [jvm]<br>override val [prefix](index.html#396403253%2FProperties%2F-134779887): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [variance](variance.html) | [jvm]<br>val [variance](variance.html): RequiredItem<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)> |

