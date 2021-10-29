---
title: CognitiveAgent
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.cognitiveagents](../index.html)/[CognitiveAgent](index.html)



# CognitiveAgent



[jvm]\
interface [CognitiveAgent](index.html)

An entity capable of having emotions and relations.



## Functions


| Name | Summary |
|---|---|
| [influencialPeople](influencial-people.html) | [jvm]<br>abstract fun [influencialPeople](influencial-people.html)(): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[CognitiveAgent](index.html)><br>A list of all the cognitive agents who exert an influence on this cognitive agent. |
| [wantsToEscape](wants-to-escape.html) | [jvm]<br>open fun [wantsToEscape](wants-to-escape.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Whether or not this pedestrian intends to escape. |


## Properties


| Name | Summary |
|---|---|
| [cognitive](cognitive.html) | [jvm]<br>abstract val [cognitive](cognitive.html): [CognitiveModel](../-cognitive-model/index.html)<br>The cognitive model this agent adheres to. |


## Inheritors


| Name |
|---|
| [CognitivePedestrian](../../it.unibo.alchemist.model.interfaces/-cognitive-pedestrian/index.html) |

