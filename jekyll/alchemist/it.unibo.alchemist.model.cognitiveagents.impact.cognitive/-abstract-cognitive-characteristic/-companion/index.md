---
title: Companion
---
//[alchemist](../../../../index.html)/[it.unibo.alchemist.model.cognitiveagents.impact.cognitive](../../index.html)/[AbstractCognitiveCharacteristic](../index.html)/[Companion](index.html)



# Companion



[jvm]\
object [Companion](index.html)

Cognitive characteristics are modeled following the principles of Network Oriented Modeling(https://doi. org/10.1007/978-3-662-58611-2_2), which allows characteristics to influence each other and evolve during the simulation. Each characteristic is modeled as an equation; weights and constant values used in equations are defined below. These are described in the [IMPACT model](https://doi.org/10.1007/978-3-319-70647-4_11).



## Properties


| Name | Summary |
|---|---|
| [advancedLogisticSigma](advanced-logistic-sigma.html) | [jvm]<br>val [advancedLogisticSigma](advanced-logistic-sigma.html): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Sigma of the [advancedLogistic](../../../it.unibo.alchemist.model.cognitiveagents.impact.cognitive.utils/advanced-logistic.html) function used to compute [Fear](../../-fear/index.html). |
| [advancedLogisticTau](advanced-logistic-tau.html) | [jvm]<br>val [advancedLogisticTau](advanced-logistic-tau.html): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Tau of the [advancedLogistic](../../../it.unibo.alchemist.model.cognitiveagents.impact.cognitive.utils/advanced-logistic.html) function used to compute [Fear](../../-fear/index.html). |
| [affectiveBiasingOmega](affective-biasing-omega.html) | [jvm]<br>val [affectiveBiasingOmega](affective-biasing-omega.html): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Influence of fear on danger belief. |
| [amplifyingEvacuationOmega](amplifying-evacuation-omega.html) | [jvm]<br>val [amplifyingEvacuationOmega](amplifying-evacuation-omega.html): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Amplifies the desire to evacuate. |
| [amplifyingFeelingOmega](amplifying-feeling-omega.html) | [jvm]<br>val [amplifyingFeelingOmega](amplifying-feeling-omega.html): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Amplifies fear sensation. |
| [amplifyingIntentionOmega](amplifying-intention-omega.html) | [jvm]<br>val [amplifyingIntentionOmega](amplifying-intention-omega.html): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Amplifies the intention to evacuate. |
| [bodyEta](body-eta.html) | [jvm]<br>val [bodyEta](body-eta.html): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Intensity of human body response. |
| [inhibitingFeelingOmega](inhibiting-feeling-omega.html) | [jvm]<br>val [inhibitingFeelingOmega](inhibiting-feeling-omega.html): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Inhibits fear sensation. |
| [inhibitingIntentionOmega](inhibiting-intention-omega.html) | [jvm]<br>val [inhibitingIntentionOmega](inhibiting-intention-omega.html): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Inhibits the intention to evacuate. |
| [inhibitingWalkRandOmega](inhibiting-walk-rand-omega.html) | [jvm]<br>val [inhibitingWalkRandOmega](inhibiting-walk-rand-omega.html): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Inhibits the desire to evacuate. |
| [logisticSigma](logistic-sigma.html) | [jvm]<br>val [logisticSigma](logistic-sigma.html): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Sigma of the [logistic](../../../it.unibo.alchemist.model.cognitiveagents.impact.cognitive.utils/logistic.html) function used to compute [IntentionEvacuate](../../-intention-evacuate/index.html) and [IntentionWalkRandomly](../../-intention-walk-randomly/index.html). |
| [logisticTau](logistic-tau.html) | [jvm]<br>val [logisticTau](logistic-tau.html): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Tau of the [logistic](../../../it.unibo.alchemist.model.cognitiveagents.impact.cognitive.utils/logistic.html) function used to compute [IntentionEvacuate](../../-intention-evacuate/index.html) and [IntentionWalkRandomly](../../-intention-walk-randomly/index.html). |
| [mentalEta](mental-eta.html) | [jvm]<br>val [mentalEta](mental-eta.html): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Intensity of human mental response. |
| [persistingOmega](persisting-omega.html) | [jvm]<br>val [persistingOmega](persisting-omega.html): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Persistence of emotions. |
| [sensingOmega](sensing-omega.html) | [jvm]<br>val [sensingOmega](sensing-omega.html): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Capacity of sensing the danger. |

