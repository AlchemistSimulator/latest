//[alchemist](../../../index.md)/[it.unibo.alchemist.model.cognitiveagents.impact.cognitive](../index.md)/[DesireEvacuate](index.md)

# DesireEvacuate

[jvm]\
class [DesireEvacuate](index.md)(**compliance**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **dangerBelief**: () -> [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **fear**: () -> [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) : [MentalCognitiveCharacteristic](../-mental-cognitive-characteristic/index.md)

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
| [DesireEvacuate](-desire-evacuate.md) | [jvm]<br>fun [DesireEvacuate](-desire-evacuate.md)(compliance: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), dangerBelief: () -> [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), fear: () -> [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>    the current level of compliance of the agent owning this. |

## Functions

| Name | Summary |
|---|---|
| [combinationFunction](combination-function.md) | [jvm]<br>open override fun [combinationFunction](combination-function.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Algorithm which decides how the parameters involved in the evolution of this characteristic must be combined together. |
| [level](../-abstract-cognitive-characteristic/level.md) | [jvm]<br>open override fun [level](../-abstract-cognitive-characteristic/level.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>The current intensity of this characteristic. |
| [update](../-mental-cognitive-characteristic/update.md) | [jvm]<br>open override fun [update](../-mental-cognitive-characteristic/update.md)(frequency: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Update the current intensity of this characteristic. |
