//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces](../index.md)/[CognitivePedestrian](index.md)

# CognitivePedestrian

[jvm]\
interface [CognitivePedestrian](index.md)<[T](index.md), [V](index.md) : [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.md)<[V](index.md)>, [A](index.md) : [GeometricTransformation](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-transformation/index.md)<[V](index.md)>> : [HeterogeneousPedestrian](../-heterogeneous-pedestrian/index.md)<[T](index.md), [V](index.md), [A](index.md)> , [CognitiveAgent](../../it.unibo.alchemist.model.cognitiveagents/-cognitive-agent/index.md)

A heterogeneous pedestrian with cognitive capabilities.

## Functions

| Name | Summary |
|---|---|
| [addReaction](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.md#-1844535178%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [addReaction](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.md#-1844535178%2FFunctions%2F-267951372)(p0: [Reaction](../-reaction/index.md)<[T](index.md)>) |
| [cloneNode](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.md#-144457153%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [cloneNode](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.md#-144457153%2FFunctions%2F-267951372)(p0: [Time](../-time/index.md)): [Node](../-node/index.md)<[T](index.md)> |
| [compareTo](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.md#1076068299%2FFunctions%2F-267951372) | [jvm]<br>abstract operator fun [compareTo](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.md#1076068299%2FFunctions%2F-267951372)(other: [Node](../-node/index.md)<[T](index.md)>): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [contains](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.md#-905365364%2FFunctions%2F-267951372) | [jvm]<br>abstract operator fun [contains](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.md#-905365364%2FFunctions%2F-267951372)(p0: [Molecule](../-molecule/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [forEach](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.md#2086990857%2FFunctions%2F-267951372) | [jvm]<br>open fun [forEach](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.md#2086990857%2FFunctions%2F-267951372)(p0: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<in [Reaction](../-reaction/index.md)<[T](index.md)>>) |
| [getConcentration](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.md#1182263796%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [getConcentration](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.md#1182263796%2FFunctions%2F-267951372)(p0: [Molecule](../-molecule/index.md)): [T](index.md) |
| [getContents](../-node/get-contents.md) | [jvm]<br>abstract fun [getContents](../-node/get-contents.md)(): [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)<[Molecule](../-molecule/index.md), [T](index.md)> |
| [getId](../-node/get-id.md) | [jvm]<br>abstract fun [getId](../-node/get-id.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getMoleculeCount](../-node/get-molecule-count.md) | [jvm]<br>abstract fun [getMoleculeCount](../-node/get-molecule-count.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getReactions](../-node/get-reactions.md) | [jvm]<br>abstract fun [getReactions](../-node/get-reactions.md)(): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)<[Reaction](../-reaction/index.md)<[T](index.md)>> |
| [influencialPeople](../../it.unibo.alchemist.model.cognitiveagents/-cognitive-agent/influencial-people.md) | [jvm]<br>abstract fun [influencialPeople](../../it.unibo.alchemist.model.cognitiveagents/-cognitive-agent/influencial-people.md)(): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[CognitiveAgent](../../it.unibo.alchemist.model.cognitiveagents/-cognitive-agent/index.md)><br>A list of all the cognitive agents who exert an influence on this cognitive agent. |
| [iterator](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.md#-1651023311%2FFunctions%2F-267951372) | [jvm]<br>abstract operator override fun [iterator](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.md#-1651023311%2FFunctions%2F-267951372)(): [MutableIterator](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-iterator/index.html)<[Reaction](../-reaction/index.md)<[T](index.md)>> |
| [probabilityOfHelping](../-heterogeneous-pedestrian/probability-of-helping.md) | [jvm]<br>abstract fun [probabilityOfHelping](../-heterogeneous-pedestrian/probability-of-helping.md)(toHelp: [HeterogeneousPedestrian](../-heterogeneous-pedestrian/index.md)<[T](index.md), [V](index.md), [A](index.md)>): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Value between 0 and 1 representing the probability this pedestrian will help another pedestrian in difficulty. |
| [removeConcentration](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.md#1461493148%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [removeConcentration](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.md#1461493148%2FFunctions%2F-267951372)(p0: [Molecule](../-molecule/index.md)) |
| [removeReaction](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.md#792936979%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [removeReaction](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.md#792936979%2FFunctions%2F-267951372)(p0: [Reaction](../-reaction/index.md)<[T](index.md)>) |
| [setConcentration](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.md#1246864287%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [setConcentration](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.md#1246864287%2FFunctions%2F-267951372)(p0: [Molecule](../-molecule/index.md), p1: [T](index.md)) |
| [speed](../-pedestrian/speed.md) | [jvm]<br>abstract fun [speed](../-pedestrian/speed.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>The speed at which the pedestrian is moving. |
| [spliterator](../../it.unibo.alchemist.loader.deployments/-close-to-g-p-s-trace/index.md#-1387152138%2FFunctions%2F-267951372) | [jvm]<br>open fun [spliterator](../../it.unibo.alchemist.loader.deployments/-close-to-g-p-s-trace/index.md#-1387152138%2FFunctions%2F-267951372)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[Reaction](../-reaction/index.md)<[T](index.md)>> |
| [wantsToEscape](../../it.unibo.alchemist.model.cognitiveagents/-cognitive-agent/wants-to-escape.md) | [jvm]<br>open fun [wantsToEscape](../../it.unibo.alchemist.model.cognitiveagents/-cognitive-agent/wants-to-escape.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Whether or not this pedestrian intends to escape. |

## Properties

| Name | Summary |
|---|---|
| [age](index.md#856337432%2FProperties%2F-267951372) | [jvm]<br>abstract val [age](index.md#856337432%2FProperties%2F-267951372): [Age](../../it.unibo.alchemist.model.cognitiveagents.impact.individual/-age/index.md)<br>The age of this pedestrian. |
| [cognitive](index.md#-1598216035%2FProperties%2F-267951372) | [jvm]<br>abstract val [cognitive](index.md#-1598216035%2FProperties%2F-267951372): [CognitiveModel](../../it.unibo.alchemist.model.cognitiveagents/-cognitive-model/index.md)<br>The cognitive model this agent adheres to. |
| [compliance](index.md#-1317738936%2FProperties%2F-267951372) | [jvm]<br>abstract val [compliance](index.md#-1317738936%2FProperties%2F-267951372): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Value between 0 and 1 representing the attitude towards conforming to social rules of this pedestrian. |
| [gender](index.md#-1796940446%2FProperties%2F-267951372) | [jvm]<br>abstract val [gender](index.md#-1796940446%2FProperties%2F-267951372): [Gender](../../it.unibo.alchemist.model.cognitiveagents.impact.individual/-gender/index.md)<br>The gender of this pedestrian. |
| [membershipGroup](index.md#885502222%2FProperties%2F-267951372) | [jvm]<br>abstract val [membershipGroup](index.md#885502222%2FProperties%2F-267951372): [PedestrianGroup](../-pedestrian-group/index.md)<[T](index.md), [V](index.md), [A](index.md)><br>The group this pedestrian belongs to. |
| [shape](index.md#-221316810%2FProperties%2F-267951372) | [jvm]<br>abstract val [shape](index.md#-221316810%2FProperties%2F-267951372): [GeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape/index.md)<[V](index.md), [A](index.md)> |

## Inheritors

| Name |
|---|
| [AbstractCognitivePedestrian](../../it.unibo.alchemist.model.implementations.nodes/-abstract-cognitive-pedestrian/index.md) |
| [CognitiveOrientingPedestrian2D](../../it.unibo.alchemist.model.implementations.nodes/-cognitive-orienting-pedestrian2-d/index.md) |
