//[alchemist](../../../../index.md)/[it.unibo.alchemist.model.cognitiveagents.impact.cognitive](../../index.md)/[AbstractCognitiveCharacteristic](../index.md)/[Companion](index.md)

# Companion

[jvm]\
object [Companion](index.md)

Cognitive characteristics are modeled following the principles of Network Oriented Modeling(https://doi. org/10.1007/978-3-662-58611-2_2), which allows characteristics to influence each other and evolve during the simulation. Each characteristic is modeled as an equation; weights and constant values used in equations are defined below. These are described in the [IMPACT model](https://doi.org/10.1007/978-3-319-70647-4_11).

## Properties

| Name | Summary |
|---|---|
| [advancedLogisticSigma](advanced-logistic-sigma.md) | [jvm]<br>val [advancedLogisticSigma](advanced-logistic-sigma.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Sigma of the [advancedLogistic](../../../it.unibo.alchemist.model.cognitiveagents.impact.cognitive.utils/advanced-logistic.md) function used to compute [Fear](../../-fear/index.md). |
| [advancedLogisticTau](advanced-logistic-tau.md) | [jvm]<br>val [advancedLogisticTau](advanced-logistic-tau.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Tau of the [advancedLogistic](../../../it.unibo.alchemist.model.cognitiveagents.impact.cognitive.utils/advanced-logistic.md) function used to compute [Fear](../../-fear/index.md). |
| [affectiveBiasingOmega](affective-biasing-omega.md) | [jvm]<br>val [affectiveBiasingOmega](affective-biasing-omega.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Influence of fear on danger belief. |
| [amplifyingEvacuationOmega](amplifying-evacuation-omega.md) | [jvm]<br>val [amplifyingEvacuationOmega](amplifying-evacuation-omega.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Amplifies the desire to evacuate. |
| [amplifyingFeelingOmega](amplifying-feeling-omega.md) | [jvm]<br>val [amplifyingFeelingOmega](amplifying-feeling-omega.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Amplifies fear sensation. |
| [amplifyingIntentionOmega](amplifying-intention-omega.md) | [jvm]<br>val [amplifyingIntentionOmega](amplifying-intention-omega.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Amplifies the intention to evacuate. |
| [bodyEta](body-eta.md) | [jvm]<br>val [bodyEta](body-eta.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Intensity of human body response. |
| [inhibitingFeelingOmega](inhibiting-feeling-omega.md) | [jvm]<br>val [inhibitingFeelingOmega](inhibiting-feeling-omega.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Inhibits fear sensation. |
| [inhibitingIntentionOmega](inhibiting-intention-omega.md) | [jvm]<br>val [inhibitingIntentionOmega](inhibiting-intention-omega.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Inhibits the intention to evacuate. |
| [inhibitingWalkRandOmega](inhibiting-walk-rand-omega.md) | [jvm]<br>val [inhibitingWalkRandOmega](inhibiting-walk-rand-omega.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Inhibits the desire to evacuate. |
| [logisticSigma](logistic-sigma.md) | [jvm]<br>val [logisticSigma](logistic-sigma.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Sigma of the [logistic](../../../it.unibo.alchemist.model.cognitiveagents.impact.cognitive.utils/logistic.md) function used to compute [IntentionEvacuate](../../-intention-evacuate/index.md) and [IntentionWalkRandomly](../../-intention-walk-randomly/index.md). |
| [logisticTau](logistic-tau.md) | [jvm]<br>val [logisticTau](logistic-tau.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Tau of the [logistic](../../../it.unibo.alchemist.model.cognitiveagents.impact.cognitive.utils/logistic.md) function used to compute [IntentionEvacuate](../../-intention-evacuate/index.md) and [IntentionWalkRandomly](../../-intention-walk-randomly/index.md). |
| [mentalEta](mental-eta.md) | [jvm]<br>val [mentalEta](mental-eta.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Intensity of human mental response. |
| [persistingOmega](persisting-omega.md) | [jvm]<br>val [persistingOmega](persisting-omega.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Persistence of emotions. |
| [sensingOmega](sensing-omega.md) | [jvm]<br>val [sensingOmega](sensing-omega.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Capacity of sensing the danger. |
