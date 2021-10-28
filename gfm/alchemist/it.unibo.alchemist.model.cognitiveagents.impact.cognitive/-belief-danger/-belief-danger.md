//[alchemist](../../../index.md)/[it.unibo.alchemist.model.cognitiveagents.impact.cognitive](../index.md)/[BeliefDanger](index.md)/[BeliefDanger](-belief-danger.md)

# BeliefDanger

[jvm]\
fun [BeliefDanger](-belief-danger.md)(zoneDangerousness: () -> [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), fear: () -> [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), influencialPeople: () -> [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[CognitiveAgent](../../it.unibo.alchemist.model.cognitiveagents/-cognitive-agent/index.md)>)

## Parameters

jvm

| | |
|---|---|
| zoneDangerousness | the influence of the position of the agent owning this     compared to the real position of the source of danger. |
| fear | the level of fear of the agent owning this. |
| influencialPeople | the list of cognitive agents with an influence on the agent owning this. |
