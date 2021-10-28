//[alchemist](../../../index.md)/[it.unibo.alchemist.model.cognitiveagents](../index.md)/[CognitiveAgent](index.md)

# CognitiveAgent

[jvm]\
interface [CognitiveAgent](index.md)

An entity capable of having emotions and relations.

## Functions

| Name | Summary |
|---|---|
| [influencialPeople](influencial-people.md) | [jvm]<br>abstract fun [influencialPeople](influencial-people.md)(): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[CognitiveAgent](index.md)><br>A list of all the cognitive agents who exert an influence on this cognitive agent. |
| [wantsToEscape](wants-to-escape.md) | [jvm]<br>open fun [wantsToEscape](wants-to-escape.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Whether or not this pedestrian intends to escape. |

## Properties

| Name | Summary |
|---|---|
| [cognitive](cognitive.md) | [jvm]<br>abstract val [cognitive](cognitive.md): [CognitiveModel](../-cognitive-model/index.md)<br>The cognitive model this agent adheres to. |

## Inheritors

| Name |
|---|
| [CognitivePedestrian](../../it.unibo.alchemist.model.interfaces/-cognitive-pedestrian/index.md) |
