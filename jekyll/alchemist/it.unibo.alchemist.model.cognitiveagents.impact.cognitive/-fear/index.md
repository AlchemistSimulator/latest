---
title: Fear
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.cognitiveagents.impact.cognitive](../index.html)/[Fear](index.html)



# Fear



[jvm]\
class [Fear](index.html)(**desireWalkRandomly**: () -> [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **desireEvacuate**: () -> [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **influencialPeople**: () -> [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[CognitiveAgent](../../it.unibo.alchemist.model.cognitiveagents/-cognitive-agent/index.html)>) : [MentalCognitiveCharacteristic](../-mental-cognitive-characteristic/index.html)

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
| [Fear](-fear.html) | [jvm]<br>fun [Fear](-fear.html)(desireWalkRandomly: () -> [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), desireEvacuate: () -> [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), influencialPeople: () -> [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[CognitiveAgent](../../it.unibo.alchemist.model.cognitiveagents/-cognitive-agent/index.html)>)<br>    the current desire of not evacuating of the agent owning this. |


## Functions


| Name | Summary |
|---|---|
| [combinationFunction](combination-function.html) | [jvm]<br>open override fun [combinationFunction](combination-function.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Algorithm which decides how the parameters involved in the evolution of this characteristic must be combined together. |
| [level](../-abstract-cognitive-characteristic/level.html) | [jvm]<br>open override fun [level](../-abstract-cognitive-characteristic/level.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>The current intensity of this characteristic. |
| [update](../-mental-cognitive-characteristic/update.html) | [jvm]<br>open override fun [update](../-mental-cognitive-characteristic/update.html)(frequency: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Update the current intensity of this characteristic. |

