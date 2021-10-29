---
title: ImpactModel
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.cognitiveagents.impact](../index.html)/[ImpactModel](index.html)



# ImpactModel



[jvm]\
class [ImpactModel](index.html)(**owner**: [CognitiveAgent](../../it.unibo.alchemist.model.cognitiveagents/-cognitive-agent/index.html), **compliance**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **environmentalFactors**: () -> [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) : [CognitiveModel](../../it.unibo.alchemist.model.cognitiveagents/-cognitive-model/index.html)

Agent-based evacuation model with social contagion mechanisms. More information can be found [here](https://doi.org/10.1007/978-3-319-70647-4_11).



## Constructors


| | |
|---|---|
| [ImpactModel](-impact-model.html) | [jvm]<br>fun [ImpactModel](-impact-model.html)(owner: [CognitiveAgent](../../it.unibo.alchemist.model.cognitiveagents/-cognitive-agent/index.html), compliance: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), environmentalFactors: () -> [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) |


## Functions


| Name | Summary |
|---|---|
| [dangerBelief](danger-belief.html) | [jvm]<br>open override fun [dangerBelief](danger-belief.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Value representing the current belief of the situation dangerousness. |
| [escapeIntention](escape-intention.html) | [jvm]<br>open override fun [escapeIntention](escape-intention.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Value representing the intention to escape. |
| [fear](fear.html) | [jvm]<br>open override fun [fear](fear.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Value representing the level of fear. |
| [remainIntention](remain-intention.html) | [jvm]<br>open override fun [remainIntention](remain-intention.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Value representing the intention to remain. |
| [update](update.html) | [jvm]<br>open override fun [update](update.html)(frequency: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Update the current intensity of the aforementioned feelings considering a [frequency](update.html). |

