---
title: it.unibo.alchemist.model.cognitiveagents.impact.cognitive
---
//[alchemist](../../index.html)/[it.unibo.alchemist.model.cognitiveagents.impact.cognitive](index.html)



# Package it.unibo.alchemist.model.cognitiveagents.impact.cognitive



## Types


| Name | Summary |
|---|---|
| [AbstractCognitiveCharacteristic](-abstract-cognitive-characteristic/index.html) | [jvm]<br>abstract class [AbstractCognitiveCharacteristic](-abstract-cognitive-characteristic/index.html) : [CognitiveCharacteristic](-cognitive-characteristic/index.html)<br>The generic implementation of a cognitive characteristic. |
| [BeliefDanger](-belief-danger/index.html) | [jvm]<br>class [BeliefDanger](-belief-danger/index.html)(**zoneDangerousness**: () -> [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **fear**: () -> [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **influencialPeople**: () -> [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[CognitiveAgent](../it.unibo.alchemist.model.cognitiveagents/-cognitive-agent/index.html)>) : [MentalCognitiveCharacteristic](-mental-cognitive-characteristic/index.html)<br>The perception of the situation dangerousness. |
| [BodyCognitiveCharacteristic](-body-cognitive-characteristic/index.html) | [jvm]<br>abstract class [BodyCognitiveCharacteristic](-body-cognitive-characteristic/index.html) : [AbstractCognitiveCharacteristic](-abstract-cognitive-characteristic/index.html)<br>A cognitive characteristic which has a body response. |
| [CognitiveCharacteristic](-cognitive-characteristic/index.html) | [jvm]<br>interface [CognitiveCharacteristic](-cognitive-characteristic/index.html) : [Characteristic](../it.unibo.alchemist.model.cognitiveagents.impact.individual/-characteristic/index.html)<br>A characteristic which depends on the other agents in the environment. |
| [CognitiveSpec](-cognitive-spec/index.html) | [jvm]<br>object [CognitiveSpec](-cognitive-spec/index.html) : ConfigSpec<br>A specification of the parameters regarding cognitive characteristics to load from a config file. |
| [DesireEvacuate](-desire-evacuate/index.html) | [jvm]<br>class [DesireEvacuate](-desire-evacuate/index.html)(**compliance**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **dangerBelief**: () -> [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **fear**: () -> [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) : [MentalCognitiveCharacteristic](-mental-cognitive-characteristic/index.html)<br>The desire to evacuate. |
| [DesireWalkRandomly](-desire-walk-randomly/index.html) | [jvm]<br>class [DesireWalkRandomly](-desire-walk-randomly/index.html)(**compliance**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **dangerBelief**: () -> [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **fear**: () -> [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) : [MentalCognitiveCharacteristic](-mental-cognitive-characteristic/index.html)<br>The desire not to evacuate. |
| [Fear](-fear/index.html) | [jvm]<br>class [Fear](-fear/index.html)(**desireWalkRandomly**: () -> [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **desireEvacuate**: () -> [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **influencialPeople**: () -> [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[CognitiveAgent](../it.unibo.alchemist.model.cognitiveagents/-cognitive-agent/index.html)>) : [MentalCognitiveCharacteristic](-mental-cognitive-characteristic/index.html)<br>The fear emotion. |
| [IntentionEvacuate](-intention-evacuate/index.html) | [jvm]<br>class [IntentionEvacuate](-intention-evacuate/index.html)(**desireWalkRandomly**: () -> [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **desireEvacuate**: () -> [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) : [BodyCognitiveCharacteristic](-body-cognitive-characteristic/index.html)<br>The intention to evacuate of . |
| [IntentionWalkRandomly](-intention-walk-randomly/index.html) | [jvm]<br>class [IntentionWalkRandomly](-intention-walk-randomly/index.html)(**desireWalkRandomly**: () -> [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **desireEvacuate**: () -> [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) : [BodyCognitiveCharacteristic](-body-cognitive-characteristic/index.html)<br>The intention not to evacuate. |
| [MentalCognitiveCharacteristic](-mental-cognitive-characteristic/index.html) | [jvm]<br>abstract class [MentalCognitiveCharacteristic](-mental-cognitive-characteristic/index.html) : [AbstractCognitiveCharacteristic](-abstract-cognitive-characteristic/index.html)<br>A cognitive characteristic which has a mental response. |

