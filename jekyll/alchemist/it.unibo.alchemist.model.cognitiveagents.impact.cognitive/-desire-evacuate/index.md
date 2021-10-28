---
title: DesireEvacuate
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.cognitiveagents.impact.cognitive](../index.html)/[DesireEvacuate](index.html)



# DesireEvacuate



[jvm]\
class [DesireEvacuate](index.html)(**compliance**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **dangerBelief**: () -> [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **fear**: () -> [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) : [MentalCognitiveCharacteristic](../-mental-cognitive-characteristic/index.html)

The desire to evacuate.



## Parameters


jvm

| | |
|---|---|
| compliance | the current level of compliance of the agent owning this. |
| dangerBelief | the current level of danger belief of the agent owning this. |
| fear | the current level of fear of the agent owning this. |



## Constructors


| | |
|---|---|
| [DesireEvacuate](-desire-evacuate.html) | [jvm]<br>fun [DesireEvacuate](-desire-evacuate.html)(compliance: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), dangerBelief: () -> [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), fear: () -> [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>    the current level of compliance of the agent owning this. |


## Functions


| Name | Summary |
|---|---|
| [combinationFunction](combination-function.html) | [jvm]<br>open override fun [combinationFunction](combination-function.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Algorithm which decides how the parameters involved in the evolution of this characteristic must be combined together. |
| [level](../-abstract-cognitive-characteristic/level.html) | [jvm]<br>open override fun [level](../-abstract-cognitive-characteristic/level.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>The current intensity of this characteristic. |
| [update](../-mental-cognitive-characteristic/update.html) | [jvm]<br>open override fun [update](../-mental-cognitive-characteristic/update.html)(frequency: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Update the current intensity of this characteristic. |

