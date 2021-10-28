---
title: ElderlyFemale
---
//[alchemist](../../../../index.html)/[it.unibo.alchemist.model.cognitiveagents.impact.individual](../../index.html)/[HelpAttitudeSpec](../index.html)/[ElderlyFemale](index.html)



# ElderlyFemale



[jvm]\
object [ElderlyFemale](index.html) : ConfigSpec

Elderly females attitudes.



## Functions


| Name | Summary |
|---|---|
| [addInnerSpec](../../-speed-spec/index.html#1157218497%2FFunctions%2F-134779887) | [jvm]<br>open override fun [addInnerSpec](../../-speed-spec/index.html#1157218497%2FFunctions%2F-134779887)(spec: Spec) |
| [addItem](../../-speed-spec/index.html#-1176720725%2FFunctions%2F-134779887) | [jvm]<br>open override fun [addItem](../../-speed-spec/index.html#-1176720725%2FFunctions%2F-134779887)(item: Item<*>) |
| [get](../../-speed-spec/index.html#216658617%2FFunctions%2F-134779887) | [jvm]<br>open operator fun [get](../../-speed-spec/index.html#216658617%2FFunctions%2F-134779887)(path: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): Spec |
| [lazy](../../-speed-spec/index.html#-57241479%2FFunctions%2F-134779887) | [jvm]<br>inline fun <[T](../../-speed-spec/index.html#-57241479%2FFunctions%2F-134779887)> [lazy](../../-speed-spec/index.html#-57241479%2FFunctions%2F-134779887)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, description: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), noinline thunk: (config: ItemContainer) -> [T](../../-speed-spec/index.html#-57241479%2FFunctions%2F-134779887)): LazyProperty<[T](../../-speed-spec/index.html#-57241479%2FFunctions%2F-134779887)> |
| [optional](../../-speed-spec/index.html#-1307546368%2FFunctions%2F-134779887) | [jvm]<br>inline fun <[T](../../-speed-spec/index.html#-1307546368%2FFunctions%2F-134779887)> [optional](../../-speed-spec/index.html#-1307546368%2FFunctions%2F-134779887)(default: [T](../../-speed-spec/index.html#-1307546368%2FFunctions%2F-134779887), name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, description: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): OptionalProperty<[T](../../-speed-spec/index.html#-1307546368%2FFunctions%2F-134779887)> |
| [plus](../../-speed-spec/index.html#-1897999851%2FFunctions%2F-134779887) | [jvm]<br>open operator fun [plus](../../-speed-spec/index.html#-1897999851%2FFunctions%2F-134779887)(spec: Spec): Spec |
| [qualify](../../-speed-spec/index.html#-620175742%2FFunctions%2F-134779887) | [jvm]<br>open fun [qualify](../../-speed-spec/index.html#-620175742%2FFunctions%2F-134779887)(item: Item<*>): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [required](../../-speed-spec/index.html#1352156512%2FFunctions%2F-134779887) | [jvm]<br>inline fun <[T](../../-speed-spec/index.html#1352156512%2FFunctions%2F-134779887)> [required](../../-speed-spec/index.html#1352156512%2FFunctions%2F-134779887)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, description: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): RequiredProperty<[T](../../-speed-spec/index.html#1352156512%2FFunctions%2F-134779887)> |
| [withFallback](../../-speed-spec/index.html#73507879%2FFunctions%2F-134779887) | [jvm]<br>open fun [withFallback](../../-speed-spec/index.html#73507879%2FFunctions%2F-134779887)(spec: Spec): Spec |
| [withPrefix](../../-speed-spec/index.html#-1060748701%2FFunctions%2F-134779887) | [jvm]<br>open fun [withPrefix](../../-speed-spec/index.html#-1060748701%2FFunctions%2F-134779887)(prefix: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): Spec |


## Properties


| Name | Summary |
|---|---|
| [adultFemale](adult-female.html) | [jvm]<br>val [adultFemale](adult-female.html): RequiredItem<[Pair](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)>> |
| [adultMale](adult-male.html) | [jvm]<br>val [adultMale](adult-male.html): RequiredItem<[Pair](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)>> |
| [childFemale](child-female.html) | [jvm]<br>val [childFemale](child-female.html): RequiredItem<[Pair](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)>> |
| [childMale](child-male.html) | [jvm]<br>val [childMale](child-male.html): RequiredItem<[Pair](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)>> |
| [elderlyFemale](elderly-female.html) | [jvm]<br>val [elderlyFemale](elderly-female.html): RequiredItem<[Pair](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)>> |
| [elderlyMale](elderly-male.html) | [jvm]<br>val [elderlyMale](elderly-male.html): RequiredItem<[Pair](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)>> |
| [innerSpecs](index.html#-1113927472%2FProperties%2F-134779887) | [jvm]<br>open override val [innerSpecs](index.html#-1113927472%2FProperties%2F-134779887): [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<Spec> |
| [items](index.html#774694056%2FProperties%2F-134779887) | [jvm]<br>open override val [items](index.html#774694056%2FProperties%2F-134779887): [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<Item<*>> |
| [prefix](index.html#-1137983968%2FProperties%2F-134779887) | [jvm]<br>override val [prefix](index.html#-1137983968%2FProperties%2F-134779887): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

