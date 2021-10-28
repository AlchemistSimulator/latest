//[alchemist](../../../index.md)/[it.unibo.alchemist.model.cognitiveagents.impact](../index.md)/[ImpactModel](index.md)

# ImpactModel

[jvm]\
class [ImpactModel](index.md)(**owner**: [CognitiveAgent](../../it.unibo.alchemist.model.cognitiveagents/-cognitive-agent/index.md), **compliance**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **environmentalFactors**: () -> [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) : [CognitiveModel](../../it.unibo.alchemist.model.cognitiveagents/-cognitive-model/index.md)

Agent-based evacuation model with social contagion mechanisms. More information can be found [here](https://doi.org/10.1007/978-3-319-70647-4_11).

## Constructors

| | |
|---|---|
| [ImpactModel](-impact-model.md) | [jvm]<br>fun [ImpactModel](-impact-model.md)(owner: [CognitiveAgent](../../it.unibo.alchemist.model.cognitiveagents/-cognitive-agent/index.md), compliance: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), environmentalFactors: () -> [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) |

## Functions

| Name | Summary |
|---|---|
| [dangerBelief](danger-belief.md) | [jvm]<br>open override fun [dangerBelief](danger-belief.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Value representing the current belief of the situation dangerousness. |
| [escapeIntention](escape-intention.md) | [jvm]<br>open override fun [escapeIntention](escape-intention.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Value representing the intention to escape. |
| [fear](fear.md) | [jvm]<br>open override fun [fear](fear.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Value representing the level of fear. |
| [remainIntention](remain-intention.md) | [jvm]<br>open override fun [remainIntention](remain-intention.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Value representing the intention to remain. |
| [update](update.md) | [jvm]<br>open override fun [update](update.md)(frequency: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Update the current intensity of the aforementioned feelings considering a [frequency](update.md). |
