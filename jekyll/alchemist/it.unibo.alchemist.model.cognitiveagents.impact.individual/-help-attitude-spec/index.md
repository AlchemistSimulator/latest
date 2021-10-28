---
title: HelpAttitudeSpec
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.cognitiveagents.impact.individual](../index.html)/[HelpAttitudeSpec](index.html)



# HelpAttitudeSpec



[jvm]\
object [HelpAttitudeSpec](index.html) : ConfigSpec

A specification of the parameters regarding help attitudes to load from a config file.



## Types


| Name | Summary |
|---|---|
| [AdultFemale](-adult-female/index.html) | [jvm]<br>object [AdultFemale](-adult-female/index.html) : ConfigSpec<br>Adult females attitudes. |
| [AdultMale](-adult-male/index.html) | [jvm]<br>object [AdultMale](-adult-male/index.html) : ConfigSpec<br>Adult males attitudes. |
| [ElderlyFemale](-elderly-female/index.html) | [jvm]<br>object [ElderlyFemale](-elderly-female/index.html) : ConfigSpec<br>Elderly females attitudes. |
| [ElderlyMale](-elderly-male/index.html) | [jvm]<br>object [ElderlyMale](-elderly-male/index.html) : ConfigSpec<br>Elderly males attitudes. |


## Functions


| Name | Summary |
|---|---|
| [addInnerSpec](../-speed-spec/index.html#1157218497%2FFunctions%2F-134779887) | [jvm]<br>open override fun [addInnerSpec](../-speed-spec/index.html#1157218497%2FFunctions%2F-134779887)(spec: Spec) |
| [addItem](../-speed-spec/index.html#-1176720725%2FFunctions%2F-134779887) | [jvm]<br>open override fun [addItem](../-speed-spec/index.html#-1176720725%2FFunctions%2F-134779887)(item: Item<*>) |
| [get](../-speed-spec/index.html#216658617%2FFunctions%2F-134779887) | [jvm]<br>open operator fun [get](../-speed-spec/index.html#216658617%2FFunctions%2F-134779887)(path: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): Spec |
| [lazy](../-speed-spec/index.html#-57241479%2FFunctions%2F-134779887) | [jvm]<br>inline fun <[T](../-speed-spec/index.html#-57241479%2FFunctions%2F-134779887)> [lazy](../-speed-spec/index.html#-57241479%2FFunctions%2F-134779887)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, description: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), noinline thunk: (config: ItemContainer) -> [T](../-speed-spec/index.html#-57241479%2FFunctions%2F-134779887)): LazyProperty<[T](../-speed-spec/index.html#-57241479%2FFunctions%2F-134779887)> |
| [optional](../-speed-spec/index.html#-1307546368%2FFunctions%2F-134779887) | [jvm]<br>inline fun <[T](../-speed-spec/index.html#-1307546368%2FFunctions%2F-134779887)> [optional](../-speed-spec/index.html#-1307546368%2FFunctions%2F-134779887)(default: [T](../-speed-spec/index.html#-1307546368%2FFunctions%2F-134779887), name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, description: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): OptionalProperty<[T](../-speed-spec/index.html#-1307546368%2FFunctions%2F-134779887)> |
| [plus](../-speed-spec/index.html#-1897999851%2FFunctions%2F-134779887) | [jvm]<br>open operator fun [plus](../-speed-spec/index.html#-1897999851%2FFunctions%2F-134779887)(spec: Spec): Spec |
| [qualify](../-speed-spec/index.html#-620175742%2FFunctions%2F-134779887) | [jvm]<br>open fun [qualify](../-speed-spec/index.html#-620175742%2FFunctions%2F-134779887)(item: Item<*>): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [required](../-speed-spec/index.html#1352156512%2FFunctions%2F-134779887) | [jvm]<br>inline fun <[T](../-speed-spec/index.html#1352156512%2FFunctions%2F-134779887)> [required](../-speed-spec/index.html#1352156512%2FFunctions%2F-134779887)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, description: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): RequiredProperty<[T](../-speed-spec/index.html#1352156512%2FFunctions%2F-134779887)> |
| [withFallback](../-speed-spec/index.html#73507879%2FFunctions%2F-134779887) | [jvm]<br>open fun [withFallback](../-speed-spec/index.html#73507879%2FFunctions%2F-134779887)(spec: Spec): Spec |
| [withPrefix](../-speed-spec/index.html#-1060748701%2FFunctions%2F-134779887) | [jvm]<br>open fun [withPrefix](../-speed-spec/index.html#-1060748701%2FFunctions%2F-134779887)(prefix: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): Spec |


## Properties


| Name | Summary |
|---|---|
| [innerSpecs](index.html#-761330725%2FProperties%2F-134779887) | [jvm]<br>open override val [innerSpecs](index.html#-761330725%2FProperties%2F-134779887): [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<Spec> |
| [items](index.html#-651053379%2FProperties%2F-134779887) | [jvm]<br>open override val [items](index.html#-651053379%2FProperties%2F-134779887): [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<Item<*>> |
| [prefix](index.html#1908485803%2FProperties%2F-134779887) | [jvm]<br>override val [prefix](index.html#1908485803%2FProperties%2F-134779887): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

