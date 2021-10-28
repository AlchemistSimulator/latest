//[alchemist](../../../index.md)/[it.unibo.alchemist.model.cognitiveagents.impact.cognitive](../index.md)/[IntentionWalkRandomly](index.md)

# IntentionWalkRandomly

[jvm]\
class [IntentionWalkRandomly](index.md)(**desireWalkRandomly**: () -> [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **desireEvacuate**: () -> [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) : [BodyCognitiveCharacteristic](../-body-cognitive-characteristic/index.md)

The intention not to evacuate.

## Parameters

jvm

| | |
|---|---|
| desireWalkRandomly | the desire not to evacuate of the agent owning this characteristic. |
| desireEvacuate | the desire to evacuate of the agent owning this characteristic. |

## Constructors

| | |
|---|---|
| [IntentionWalkRandomly](-intention-walk-randomly.md) | [jvm]<br>fun [IntentionWalkRandomly](-intention-walk-randomly.md)(desireWalkRandomly: () -> [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), desireEvacuate: () -> [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>    the desire not to evacuate of the agent owning this characteristic. |

## Functions

| Name | Summary |
|---|---|
| [combinationFunction](combination-function.md) | [jvm]<br>open override fun [combinationFunction](combination-function.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Algorithm which decides how the parameters involved in the evolution of this characteristic must be combined together. |
| [level](../-abstract-cognitive-characteristic/level.md) | [jvm]<br>open override fun [level](../-abstract-cognitive-characteristic/level.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>The current intensity of this characteristic. |
| [update](../-body-cognitive-characteristic/update.md) | [jvm]<br>open override fun [update](../-body-cognitive-characteristic/update.md)(frequency: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Update the current intensity of this characteristic. |