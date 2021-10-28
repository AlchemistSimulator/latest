//[alchemist](../../../index.md)/[it.unibo.alchemist.model.cognitiveagents.impact.cognitive](../index.md)/[Fear](index.md)

# Fear

[jvm]\
class [Fear](index.md)(**desireWalkRandomly**: () -> [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **desireEvacuate**: () -> [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **influencialPeople**: () -> [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[CognitiveAgent](../../it.unibo.alchemist.model.cognitiveagents/-cognitive-agent/index.md)>) : [MentalCognitiveCharacteristic](../-mental-cognitive-characteristic/index.md)

The fear emotion.

## Parameters

jvm

| | |
|---|---|
| desireWalkRandomly | the current desire of not evacuating of the agent owning this. |
| desireEvacuate | the current desire of evacuating of the agent owning this. |
| influencialPeople | the list of cognitive agents with an influence on the agent owning this. |

## Constructors

| | |
|---|---|
| [Fear](-fear.md) | [jvm]<br>fun [Fear](-fear.md)(desireWalkRandomly: () -> [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), desireEvacuate: () -> [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), influencialPeople: () -> [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[CognitiveAgent](../../it.unibo.alchemist.model.cognitiveagents/-cognitive-agent/index.md)>)<br>    the current desire of not evacuating of the agent owning this. |

## Functions

| Name | Summary |
|---|---|
| [combinationFunction](combination-function.md) | [jvm]<br>open override fun [combinationFunction](combination-function.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Algorithm which decides how the parameters involved in the evolution of this characteristic must be combined together. |
| [level](../-abstract-cognitive-characteristic/level.md) | [jvm]<br>open override fun [level](../-abstract-cognitive-characteristic/level.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>The current intensity of this characteristic. |
| [update](../-mental-cognitive-characteristic/update.md) | [jvm]<br>open override fun [update](../-mental-cognitive-characteristic/update.md)(frequency: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Update the current intensity of this characteristic. |
