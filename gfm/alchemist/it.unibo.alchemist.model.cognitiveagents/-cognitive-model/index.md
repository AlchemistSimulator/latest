//[alchemist](../../../index.md)/[it.unibo.alchemist.model.cognitiveagents](../index.md)/[CognitiveModel](index.md)

# CognitiveModel

[jvm]\
interface [CognitiveModel](index.md)

Theoretical model to describe the cognitive processes underlying in an agent.

## Functions

| Name | Summary |
|---|---|
| [dangerBelief](danger-belief.md) | [jvm]<br>abstract fun [dangerBelief](danger-belief.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Value representing the current belief of the situation dangerousness. |
| [escapeIntention](escape-intention.md) | [jvm]<br>abstract fun [escapeIntention](escape-intention.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Value representing the intention to escape. |
| [fear](fear.md) | [jvm]<br>abstract fun [fear](fear.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Value representing the level of fear. |
| [remainIntention](remain-intention.md) | [jvm]<br>abstract fun [remainIntention](remain-intention.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Value representing the intention to remain. |
| [update](update.md) | [jvm]<br>abstract fun [update](update.md)(frequency: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Update the current intensity of the aforementioned feelings considering a [frequency](update.md). |

## Inheritors

| Name |
|---|
| [ImpactModel](../../it.unibo.alchemist.model.cognitiveagents.impact/-impact-model/index.md) |
