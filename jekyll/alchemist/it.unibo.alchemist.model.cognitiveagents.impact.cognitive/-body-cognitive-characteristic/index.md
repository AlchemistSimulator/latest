---
title: BodyCognitiveCharacteristic
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.cognitiveagents.impact.cognitive](../index.html)/[BodyCognitiveCharacteristic](index.html)



# BodyCognitiveCharacteristic



[jvm]\
abstract class [BodyCognitiveCharacteristic](index.html) : [AbstractCognitiveCharacteristic](../-abstract-cognitive-characteristic/index.html)

A cognitive characteristic which has a body response.



## Constructors


| | |
|---|---|
| [BodyCognitiveCharacteristic](-body-cognitive-characteristic.html) | [jvm]<br>fun [BodyCognitiveCharacteristic](-body-cognitive-characteristic.html)() |


## Functions


| Name | Summary |
|---|---|
| [combinationFunction](../-abstract-cognitive-characteristic/combination-function.html) | [jvm]<br>abstract fun [combinationFunction](../-abstract-cognitive-characteristic/combination-function.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Algorithm which decides how the parameters involved in the evolution of this characteristic must be combined together. |
| [level](../-abstract-cognitive-characteristic/level.html) | [jvm]<br>open override fun [level](../-abstract-cognitive-characteristic/level.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>The current intensity of this characteristic. |
| [update](update.html) | [jvm]<br>open override fun [update](update.html)(frequency: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Update the current intensity of this characteristic. |


## Inheritors


| Name |
|---|
| [IntentionEvacuate](../-intention-evacuate/index.html) |
| [IntentionWalkRandomly](../-intention-walk-randomly/index.html) |

