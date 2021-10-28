//[alchemist](../../../index.md)/[it.unibo.alchemist.model.cognitiveagents.impact.cognitive](../index.md)/[CognitiveSpec](index.md)

# CognitiveSpec

[jvm]\
object [CognitiveSpec](index.md) : ConfigSpec

A specification of the parameters regarding cognitive characteristics to load from a config file.

## Functions

| Name | Summary |
|---|---|
| [addInnerSpec](../../it.unibo.alchemist.model.cognitiveagents.impact.individual/-speed-spec/index.md#1157218497%2FFunctions%2F-267951372) | [jvm]<br>open override fun [addInnerSpec](../../it.unibo.alchemist.model.cognitiveagents.impact.individual/-speed-spec/index.md#1157218497%2FFunctions%2F-267951372)(spec: Spec) |
| [addItem](../../it.unibo.alchemist.model.cognitiveagents.impact.individual/-speed-spec/index.md#-1176720725%2FFunctions%2F-267951372) | [jvm]<br>open override fun [addItem](../../it.unibo.alchemist.model.cognitiveagents.impact.individual/-speed-spec/index.md#-1176720725%2FFunctions%2F-267951372)(item: Item<*>) |
| [get](../../it.unibo.alchemist.model.cognitiveagents.impact.individual/-speed-spec/index.md#216658617%2FFunctions%2F-267951372) | [jvm]<br>open operator fun [get](../../it.unibo.alchemist.model.cognitiveagents.impact.individual/-speed-spec/index.md#216658617%2FFunctions%2F-267951372)(path: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): Spec |
| [lazy](../../it.unibo.alchemist.model.cognitiveagents.impact.individual/-speed-spec/index.md#-57241479%2FFunctions%2F-267951372) | [jvm]<br>inline fun <[T](../../it.unibo.alchemist.model.cognitiveagents.impact.individual/-speed-spec/index.md#-57241479%2FFunctions%2F-267951372)> [lazy](../../it.unibo.alchemist.model.cognitiveagents.impact.individual/-speed-spec/index.md#-57241479%2FFunctions%2F-267951372)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, description: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), noinline thunk: (config: ItemContainer) -> [T](../../it.unibo.alchemist.model.cognitiveagents.impact.individual/-speed-spec/index.md#-57241479%2FFunctions%2F-267951372)): LazyProperty<[T](../../it.unibo.alchemist.model.cognitiveagents.impact.individual/-speed-spec/index.md#-57241479%2FFunctions%2F-267951372)> |
| [optional](../../it.unibo.alchemist.model.cognitiveagents.impact.individual/-speed-spec/index.md#-1307546368%2FFunctions%2F-267951372) | [jvm]<br>inline fun <[T](../../it.unibo.alchemist.model.cognitiveagents.impact.individual/-speed-spec/index.md#-1307546368%2FFunctions%2F-267951372)> [optional](../../it.unibo.alchemist.model.cognitiveagents.impact.individual/-speed-spec/index.md#-1307546368%2FFunctions%2F-267951372)(default: [T](../../it.unibo.alchemist.model.cognitiveagents.impact.individual/-speed-spec/index.md#-1307546368%2FFunctions%2F-267951372), name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, description: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): OptionalProperty<[T](../../it.unibo.alchemist.model.cognitiveagents.impact.individual/-speed-spec/index.md#-1307546368%2FFunctions%2F-267951372)> |
| [plus](../../it.unibo.alchemist.model.cognitiveagents.impact.individual/-speed-spec/index.md#-1897999851%2FFunctions%2F-267951372) | [jvm]<br>open operator fun [plus](../../it.unibo.alchemist.model.cognitiveagents.impact.individual/-speed-spec/index.md#-1897999851%2FFunctions%2F-267951372)(spec: Spec): Spec |
| [qualify](../../it.unibo.alchemist.model.cognitiveagents.impact.individual/-speed-spec/index.md#-620175742%2FFunctions%2F-267951372) | [jvm]<br>open fun [qualify](../../it.unibo.alchemist.model.cognitiveagents.impact.individual/-speed-spec/index.md#-620175742%2FFunctions%2F-267951372)(item: Item<*>): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [required](../../it.unibo.alchemist.model.cognitiveagents.impact.individual/-speed-spec/index.md#1352156512%2FFunctions%2F-267951372) | [jvm]<br>inline fun <[T](../../it.unibo.alchemist.model.cognitiveagents.impact.individual/-speed-spec/index.md#1352156512%2FFunctions%2F-267951372)> [required](../../it.unibo.alchemist.model.cognitiveagents.impact.individual/-speed-spec/index.md#1352156512%2FFunctions%2F-267951372)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, description: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): RequiredProperty<[T](../../it.unibo.alchemist.model.cognitiveagents.impact.individual/-speed-spec/index.md#1352156512%2FFunctions%2F-267951372)> |
| [withFallback](../../it.unibo.alchemist.model.cognitiveagents.impact.individual/-speed-spec/index.md#73507879%2FFunctions%2F-267951372) | [jvm]<br>open fun [withFallback](../../it.unibo.alchemist.model.cognitiveagents.impact.individual/-speed-spec/index.md#73507879%2FFunctions%2F-267951372)(spec: Spec): Spec |
| [withPrefix](../../it.unibo.alchemist.model.cognitiveagents.impact.individual/-speed-spec/index.md#-1060748701%2FFunctions%2F-267951372) | [jvm]<br>open fun [withPrefix](../../it.unibo.alchemist.model.cognitiveagents.impact.individual/-speed-spec/index.md#-1060748701%2FFunctions%2F-267951372)(prefix: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): Spec |

## Properties

| Name | Summary |
|---|---|
| [advancedLogisticSigma](advanced-logistic-sigma.md) | [jvm]<br>val [advancedLogisticSigma](advanced-logistic-sigma.md): RequiredItem<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)> |
| [advancedLogisticTau](advanced-logistic-tau.md) | [jvm]<br>val [advancedLogisticTau](advanced-logistic-tau.md): RequiredItem<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)> |
| [affectiveBiasingOmega](affective-biasing-omega.md) | [jvm]<br>val [affectiveBiasingOmega](affective-biasing-omega.md): RequiredItem<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)> |
| [amplifyingEvacuationOmega](amplifying-evacuation-omega.md) | [jvm]<br>val [amplifyingEvacuationOmega](amplifying-evacuation-omega.md): RequiredItem<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)> |
| [amplifyingFeelingOmega](amplifying-feeling-omega.md) | [jvm]<br>val [amplifyingFeelingOmega](amplifying-feeling-omega.md): RequiredItem<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)> |
| [amplifyingIntentionOmega](amplifying-intention-omega.md) | [jvm]<br>val [amplifyingIntentionOmega](amplifying-intention-omega.md): RequiredItem<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)> |
| [bodyEta](body-eta.md) | [jvm]<br>val [bodyEta](body-eta.md): RequiredItem<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)> |
| [inhibitingFeelingOmega](inhibiting-feeling-omega.md) | [jvm]<br>val [inhibitingFeelingOmega](inhibiting-feeling-omega.md): RequiredItem<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)> |
| [inhibitingIntentionOmega](inhibiting-intention-omega.md) | [jvm]<br>val [inhibitingIntentionOmega](inhibiting-intention-omega.md): RequiredItem<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)> |
| [inhibitingWalkRandOmega](inhibiting-walk-rand-omega.md) | [jvm]<br>val [inhibitingWalkRandOmega](inhibiting-walk-rand-omega.md): RequiredItem<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)> |
| [innerSpecs](index.md#-87167681%2FProperties%2F-267951372) | [jvm]<br>open override val [innerSpecs](index.md#-87167681%2FProperties%2F-267951372): [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<Spec> |
| [items](index.md#455573209%2FProperties%2F-267951372) | [jvm]<br>open override val [items](index.md#455573209%2FProperties%2F-267951372): [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<Item<*>> |
| [logisticSigma](logistic-sigma.md) | [jvm]<br>val [logisticSigma](logistic-sigma.md): RequiredItem<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)> |
| [logisticTau](logistic-tau.md) | [jvm]<br>val [logisticTau](logistic-tau.md): RequiredItem<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)> |
| [mentalEta](mental-eta.md) | [jvm]<br>val [mentalEta](mental-eta.md): RequiredItem<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)> |
| [persistingOmega](persisting-omega.md) | [jvm]<br>val [persistingOmega](persisting-omega.md): RequiredItem<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)> |
| [prefix](index.md#1854171663%2FProperties%2F-267951372) | [jvm]<br>override val [prefix](index.md#1854171663%2FProperties%2F-267951372): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [sensingOmega](sensing-omega.md) | [jvm]<br>val [sensingOmega](sensing-omega.md): RequiredItem<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)> |
