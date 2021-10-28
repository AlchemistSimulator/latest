---
title: AbstractCognitiveCharacteristic
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.cognitiveagents.impact.cognitive](../index.html)/[AbstractCognitiveCharacteristic](index.html)



# AbstractCognitiveCharacteristic



[jvm]\
abstract class [AbstractCognitiveCharacteristic](index.html) : [CognitiveCharacteristic](../-cognitive-characteristic/index.html)

The generic implementation of a cognitive characteristic.



## Constructors


| | |
|---|---|
| [AbstractCognitiveCharacteristic](-abstract-cognitive-characteristic.html) | [jvm]<br>fun [AbstractCognitiveCharacteristic](-abstract-cognitive-characteristic.html)() |


## Types


| Name | Summary |
|---|---|
| [Companion](-companion/index.html) | [jvm]<br>object [Companion](-companion/index.html)<br>Cognitive characteristics are modeled following the principles of Network Oriented Modeling(https://doi. |


## Functions


| Name | Summary |
|---|---|
| [combinationFunction](combination-function.html) | [jvm]<br>abstract fun [combinationFunction](combination-function.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Algorithm which decides how the parameters involved in the evolution of this characteristic must be combined together. |
| [level](level.html) | [jvm]<br>open override fun [level](level.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>The current intensity of this characteristic. |
| [update](../-cognitive-characteristic/update.html) | [jvm]<br>abstract fun [update](../-cognitive-characteristic/update.html)(frequency: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Update the current intensity of this characteristic. |


## Inheritors


| Name |
|---|
| [BodyCognitiveCharacteristic](../-body-cognitive-characteristic/index.html) |
| [MentalCognitiveCharacteristic](../-mental-cognitive-characteristic/index.html) |

