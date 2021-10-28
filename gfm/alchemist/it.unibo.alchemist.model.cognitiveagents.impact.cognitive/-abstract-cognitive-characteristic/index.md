//[alchemist](../../../index.md)/[it.unibo.alchemist.model.cognitiveagents.impact.cognitive](../index.md)/[AbstractCognitiveCharacteristic](index.md)

# AbstractCognitiveCharacteristic

[jvm]\
abstract class [AbstractCognitiveCharacteristic](index.md) : [CognitiveCharacteristic](../-cognitive-characteristic/index.md)

The generic implementation of a cognitive characteristic.

## Constructors

| | |
|---|---|
| [AbstractCognitiveCharacteristic](-abstract-cognitive-characteristic.md) | [jvm]<br>fun [AbstractCognitiveCharacteristic](-abstract-cognitive-characteristic.md)() |

## Types

| Name | Summary |
|---|---|
| [Companion](-companion/index.md) | [jvm]<br>object [Companion](-companion/index.md)<br>Cognitive characteristics are modeled following the principles of Network Oriented Modeling(https://doi. |

## Functions

| Name | Summary |
|---|---|
| [combinationFunction](combination-function.md) | [jvm]<br>abstract fun [combinationFunction](combination-function.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Algorithm which decides how the parameters involved in the evolution of this characteristic must be combined together. |
| [level](level.md) | [jvm]<br>open override fun [level](level.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>The current intensity of this characteristic. |
| [update](../-cognitive-characteristic/update.md) | [jvm]<br>abstract fun [update](../-cognitive-characteristic/update.md)(frequency: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Update the current intensity of this characteristic. |

## Inheritors

| Name |
|---|
| [BodyCognitiveCharacteristic](../-body-cognitive-characteristic/index.md) |
| [MentalCognitiveCharacteristic](../-mental-cognitive-characteristic/index.md) |
