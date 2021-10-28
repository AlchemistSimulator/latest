//[alchemist](../../../index.md)/[it.unibo.alchemist.model.cognitiveagents.impact.cognitive](../index.md)/[MentalCognitiveCharacteristic](index.md)

# MentalCognitiveCharacteristic

[jvm]\
abstract class [MentalCognitiveCharacteristic](index.md) : [AbstractCognitiveCharacteristic](../-abstract-cognitive-characteristic/index.md)

A cognitive characteristic which has a mental response.

## Constructors

| | |
|---|---|
| [MentalCognitiveCharacteristic](-mental-cognitive-characteristic.md) | [jvm]<br>fun [MentalCognitiveCharacteristic](-mental-cognitive-characteristic.md)() |

## Functions

| Name | Summary |
|---|---|
| [combinationFunction](../-abstract-cognitive-characteristic/combination-function.md) | [jvm]<br>abstract fun [combinationFunction](../-abstract-cognitive-characteristic/combination-function.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Algorithm which decides how the parameters involved in the evolution of this characteristic must be combined together. |
| [level](../-abstract-cognitive-characteristic/level.md) | [jvm]<br>open override fun [level](../-abstract-cognitive-characteristic/level.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>The current intensity of this characteristic. |
| [update](update.md) | [jvm]<br>open override fun [update](update.md)(frequency: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Update the current intensity of this characteristic. |

## Inheritors

| Name |
|---|
| [BeliefDanger](../-belief-danger/index.md) |
| [DesireEvacuate](../-desire-evacuate/index.md) |
| [DesireWalkRandomly](../-desire-walk-randomly/index.md) |
| [Fear](../-fear/index.md) |
