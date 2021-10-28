//[alchemist](../../index.md)/[it.unibo.alchemist.model.cognitiveagents.impact.cognitive](index.md)

# Package it.unibo.alchemist.model.cognitiveagents.impact.cognitive

## Types

| Name | Summary |
|---|---|
| [AbstractCognitiveCharacteristic](-abstract-cognitive-characteristic/index.md) | [jvm]<br>abstract class [AbstractCognitiveCharacteristic](-abstract-cognitive-characteristic/index.md) : [CognitiveCharacteristic](-cognitive-characteristic/index.md)<br>The generic implementation of a cognitive characteristic. |
| [BeliefDanger](-belief-danger/index.md) | [jvm]<br>class [BeliefDanger](-belief-danger/index.md)(**zoneDangerousness**: () -> [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **fear**: () -> [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **influencialPeople**: () -> [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[CognitiveAgent](../it.unibo.alchemist.model.cognitiveagents/-cognitive-agent/index.md)>) : [MentalCognitiveCharacteristic](-mental-cognitive-characteristic/index.md)<br>The perception of the situation dangerousness. |
| [BodyCognitiveCharacteristic](-body-cognitive-characteristic/index.md) | [jvm]<br>abstract class [BodyCognitiveCharacteristic](-body-cognitive-characteristic/index.md) : [AbstractCognitiveCharacteristic](-abstract-cognitive-characteristic/index.md)<br>A cognitive characteristic which has a body response. |
| [CognitiveCharacteristic](-cognitive-characteristic/index.md) | [jvm]<br>interface [CognitiveCharacteristic](-cognitive-characteristic/index.md) : [Characteristic](../it.unibo.alchemist.model.cognitiveagents.impact.individual/-characteristic/index.md)<br>A characteristic which depends on the other agents in the environment. |
| [CognitiveSpec](-cognitive-spec/index.md) | [jvm]<br>object [CognitiveSpec](-cognitive-spec/index.md) : ConfigSpec<br>A specification of the parameters regarding cognitive characteristics to load from a config file. |
| [DesireEvacuate](-desire-evacuate/index.md) | [jvm]<br>class [DesireEvacuate](-desire-evacuate/index.md)(**compliance**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **dangerBelief**: () -> [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **fear**: () -> [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) : [MentalCognitiveCharacteristic](-mental-cognitive-characteristic/index.md)<br>The desire to evacuate. |
| [DesireWalkRandomly](-desire-walk-randomly/index.md) | [jvm]<br>class [DesireWalkRandomly](-desire-walk-randomly/index.md)(**compliance**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **dangerBelief**: () -> [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **fear**: () -> [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) : [MentalCognitiveCharacteristic](-mental-cognitive-characteristic/index.md)<br>The desire not to evacuate. |
| [Fear](-fear/index.md) | [jvm]<br>class [Fear](-fear/index.md)(**desireWalkRandomly**: () -> [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **desireEvacuate**: () -> [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **influencialPeople**: () -> [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[CognitiveAgent](../it.unibo.alchemist.model.cognitiveagents/-cognitive-agent/index.md)>) : [MentalCognitiveCharacteristic](-mental-cognitive-characteristic/index.md)<br>The fear emotion. |
| [IntentionEvacuate](-intention-evacuate/index.md) | [jvm]<br>class [IntentionEvacuate](-intention-evacuate/index.md)(**desireWalkRandomly**: () -> [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **desireEvacuate**: () -> [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) : [BodyCognitiveCharacteristic](-body-cognitive-characteristic/index.md)<br>The intention to evacuate of . |
| [IntentionWalkRandomly](-intention-walk-randomly/index.md) | [jvm]<br>class [IntentionWalkRandomly](-intention-walk-randomly/index.md)(**desireWalkRandomly**: () -> [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **desireEvacuate**: () -> [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) : [BodyCognitiveCharacteristic](-body-cognitive-characteristic/index.md)<br>The intention not to evacuate. |
| [MentalCognitiveCharacteristic](-mental-cognitive-characteristic/index.md) | [jvm]<br>abstract class [MentalCognitiveCharacteristic](-mental-cognitive-characteristic/index.md) : [AbstractCognitiveCharacteristic](-abstract-cognitive-characteristic/index.md)<br>A cognitive characteristic which has a mental response. |