---
title: MentalCognitiveCharacteristic
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.cognitiveagents.impact.cognitive](../index.html)/[MentalCognitiveCharacteristic](index.html)



# MentalCognitiveCharacteristic



[jvm]\
abstract class [MentalCognitiveCharacteristic](index.html) : [AbstractCognitiveCharacteristic](../-abstract-cognitive-characteristic/index.html)

A cognitive characteristic which has a mental response.



## Constructors


| | |
|---|---|
| [MentalCognitiveCharacteristic](-mental-cognitive-characteristic.html) | [jvm]<br>fun [MentalCognitiveCharacteristic](-mental-cognitive-characteristic.html)() |


## Functions


| Name | Summary |
|---|---|
| [combinationFunction](../-abstract-cognitive-characteristic/combination-function.html) | [jvm]<br>abstract fun [combinationFunction](../-abstract-cognitive-characteristic/combination-function.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Algorithm which decides how the parameters involved in the evolution of this characteristic must be combined together. |
| [level](../-abstract-cognitive-characteristic/level.html) | [jvm]<br>open override fun [level](../-abstract-cognitive-characteristic/level.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>The current intensity of this characteristic. |
| [update](update.html) | [jvm]<br>open override fun [update](update.html)(frequency: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Update the current intensity of this characteristic. |


## Inheritors


| Name |
|---|
| [BeliefDanger](../-belief-danger/index.html) |
| [DesireEvacuate](../-desire-evacuate/index.html) |
| [DesireWalkRandomly](../-desire-walk-randomly/index.html) |
| [Fear](../-fear/index.html) |

