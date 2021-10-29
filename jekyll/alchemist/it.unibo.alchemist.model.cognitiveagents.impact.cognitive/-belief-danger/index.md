---
title: BeliefDanger
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.cognitiveagents.impact.cognitive](../index.html)/[BeliefDanger](index.html)



# BeliefDanger



[jvm]\
class [BeliefDanger](index.html)(**zoneDangerousness**: () -> [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **fear**: () -> [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **influencialPeople**: () -> [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[CognitiveAgent](../../it.unibo.alchemist.model.cognitiveagents/-cognitive-agent/index.html)>) : [MentalCognitiveCharacteristic](../-mental-cognitive-characteristic/index.html)

The perception of the situation dangerousness. The name belief derives from the [IMPACT model](https://doi.org/10.1007/978-3-319-70647-4_11).



## Parameters


jvm

| | |
|---|---|
| zoneDangerousness | the influence of the position of the agent owning this     compared to the real position of the source of danger. |
| fear | the level of fear of the agent owning this. |
| influencialPeople | the list of cognitive agents with an influence on the agent owning this. |



## Constructors


| | |
|---|---|
| [BeliefDanger](-belief-danger.html) | [jvm]<br>fun [BeliefDanger](-belief-danger.html)(zoneDangerousness: () -> [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), fear: () -> [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), influencialPeople: () -> [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[CognitiveAgent](../../it.unibo.alchemist.model.cognitiveagents/-cognitive-agent/index.html)>)<br>    the influence of the position of the agent owning this     compared to the real position of the source of danger. |


## Functions


| Name | Summary |
|---|---|
| [combinationFunction](combination-function.html) | [jvm]<br>open override fun [combinationFunction](combination-function.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Algorithm which decides how the parameters involved in the evolution of this characteristic must be combined together. |
| [level](../-abstract-cognitive-characteristic/level.html) | [jvm]<br>open override fun [level](../-abstract-cognitive-characteristic/level.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>The current intensity of this characteristic. |
| [update](../-mental-cognitive-characteristic/update.html) | [jvm]<br>open override fun [update](../-mental-cognitive-characteristic/update.html)(frequency: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Update the current intensity of this characteristic. |

