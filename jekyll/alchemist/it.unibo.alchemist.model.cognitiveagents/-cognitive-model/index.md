---
title: CognitiveModel
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.cognitiveagents](../index.html)/[CognitiveModel](index.html)



# CognitiveModel



[jvm]\
interface [CognitiveModel](index.html)

Theoretical model to describe the cognitive processes underlying in an agent.



## Functions


| Name | Summary |
|---|---|
| [dangerBelief](danger-belief.html) | [jvm]<br>abstract fun [dangerBelief](danger-belief.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Value representing the current belief of the situation dangerousness. |
| [escapeIntention](escape-intention.html) | [jvm]<br>abstract fun [escapeIntention](escape-intention.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Value representing the intention to escape. |
| [fear](fear.html) | [jvm]<br>abstract fun [fear](fear.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Value representing the level of fear. |
| [remainIntention](remain-intention.html) | [jvm]<br>abstract fun [remainIntention](remain-intention.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Value representing the intention to remain. |
| [update](update.html) | [jvm]<br>abstract fun [update](update.html)(frequency: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Update the current intensity of the aforementioned feelings considering a [frequency](update.html). |


## Inheritors


| Name |
|---|
| [ImpactModel](../../it.unibo.alchemist.model.cognitiveagents.impact/-impact-model/index.html) |

