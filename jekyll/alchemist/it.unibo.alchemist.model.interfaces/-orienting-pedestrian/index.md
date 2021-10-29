---
title: OrientingPedestrian
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces](../index.html)/[OrientingPedestrian](index.html)



# OrientingPedestrian



[jvm]\
interface [OrientingPedestrian](index.html)<[T](index.html), [V](index.html) : [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html)<[V](index.html)>, [A](index.html) : [GeometricTransformation](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-transformation/index.html)<[V](index.html)>, [L](index.html) : [ConvexGeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-convex-geometric-shape/index.html)<[V](index.html), [A](index.html)>, [R](index.html)> : [Pedestrian](../-pedestrian/index.html)<[T](index.html), [V](index.html), [A](index.html)> , [OrientingAgent](../-orienting-agent/index.html)<[V](index.html), [A](index.html), [L](index.html), [R](index.html)> 

A pedestrian capable of orienting itself.



## Parameters


jvm

| | |
|---|---|
| T | the concentration type. |
| V | the [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html) type for the space this pedestrian is inside. |
| A | the transformations supported by the shapes in this space. |
| L | the type of landmarks stored in the pedestrian's [cognitiveMap](index.html#286553924%2FProperties%2F-134779887). |
| R | the type of edges of the [cognitiveMap](index.html#286553924%2FProperties%2F-134779887), representing the [R](index.html)elations between landmarks. |



## Functions


| Name | Summary |
|---|---|
| [addReaction](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.html#-1844535178%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [addReaction](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.html#-1844535178%2FFunctions%2F-134779887)(p0: [Reaction](../-reaction/index.html)<[T](index.html)>) |
| [cloneNode](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.html#-144457153%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [cloneNode](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.html#-144457153%2FFunctions%2F-134779887)(p0: [Time](../-time/index.html)): [Node](../-node/index.html)<[T](index.html)> |
| [compareTo](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.html#1076068299%2FFunctions%2F-134779887) | [jvm]<br>abstract operator fun [compareTo](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.html#1076068299%2FFunctions%2F-134779887)(other: [Node](../-node/index.html)<[T](index.html)>): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [contains](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.html#-905365364%2FFunctions%2F-134779887) | [jvm]<br>abstract operator fun [contains](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.html#-905365364%2FFunctions%2F-134779887)(p0: [Molecule](../-molecule/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [forEach](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.html#2086990857%2FFunctions%2F-134779887) | [jvm]<br>open fun [forEach](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.html#2086990857%2FFunctions%2F-134779887)(p0: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<in [Reaction](../-reaction/index.html)<[T](index.html)>>) |
| [getConcentration](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.html#1182263796%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [getConcentration](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.html#1182263796%2FFunctions%2F-134779887)(p0: [Molecule](../-molecule/index.html)): [T](index.html) |
| [getContents](../-node/get-contents.html) | [jvm]<br>abstract fun [getContents](../-node/get-contents.html)(): [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)<[Molecule](../-molecule/index.html), [T](index.html)> |
| [getId](../-node/get-id.html) | [jvm]<br>abstract fun [getId](../-node/get-id.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getMoleculeCount](../-node/get-molecule-count.html) | [jvm]<br>abstract fun [getMoleculeCount](../-node/get-molecule-count.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getReactions](../-node/get-reactions.html) | [jvm]<br>abstract fun [getReactions](../-node/get-reactions.html)(): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)<[Reaction](../-reaction/index.html)<[T](index.html)>> |
| [iterator](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.html#-1651023311%2FFunctions%2F-134779887) | [jvm]<br>abstract operator override fun [iterator](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.html#-1651023311%2FFunctions%2F-134779887)(): [MutableIterator](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-iterator/index.html)<[Reaction](../-reaction/index.html)<[T](index.html)>> |
| [registerVisit](../-orienting-agent/register-visit.html) | [jvm]<br>open fun <[M](../-orienting-agent/register-visit.html) : [ConvexGeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-convex-geometric-shape/index.html)<[V](index.html), [A](index.html)>> [registerVisit](../-orienting-agent/register-visit.html)(area: [M](../-orienting-agent/register-visit.html))<br>Registers a visit to the provided [area](../-orienting-agent/register-visit.html) in the agent's [volatileMemory](../-orienting-agent/volatile-memory.html). |
| [removeConcentration](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.html#1461493148%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [removeConcentration](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.html#1461493148%2FFunctions%2F-134779887)(p0: [Molecule](../-molecule/index.html)) |
| [removeReaction](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.html#792936979%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [removeReaction](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.html#792936979%2FFunctions%2F-134779887)(p0: [Reaction](../-reaction/index.html)<[T](index.html)>) |
| [setConcentration](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.html#1246864287%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [setConcentration](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.html#1246864287%2FFunctions%2F-134779887)(p0: [Molecule](../-molecule/index.html), p1: [T](index.html)) |
| [speed](../-pedestrian/speed.html) | [jvm]<br>abstract fun [speed](../-pedestrian/speed.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>The speed at which the pedestrian is moving. |
| [spliterator](../../it.unibo.alchemist.loader.deployments/-close-to-g-p-s-trace/index.html#-1387152138%2FFunctions%2F-134779887) | [jvm]<br>open fun [spliterator](../../it.unibo.alchemist.loader.deployments/-close-to-g-p-s-trace/index.html#-1387152138%2FFunctions%2F-134779887)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[Reaction](../-reaction/index.html)<[T](index.html)>> |


## Properties


| Name | Summary |
|---|---|
| [cognitiveMap](index.html#286553924%2FProperties%2F-134779887) | [jvm]<br>abstract val [cognitiveMap](index.html#286553924%2FProperties%2F-134779887): [NavigationGraph](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d.graph/-navigation-graph/index.html)<[V](index.html), [A](index.html), [L](index.html), [R](index.html)><br>The cognitive map of the agent. |
| [knowledgeDegree](index.html#-789048694%2FProperties%2F-134779887) | [jvm]<br>abstract val [knowledgeDegree](index.html#-789048694%2FProperties%2F-134779887): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>The knowledge degree of the agent concerning the environment. |
| [membershipGroup](index.html#1856488459%2FProperties%2F-134779887) | [jvm]<br>abstract val [membershipGroup](index.html#1856488459%2FProperties%2F-134779887): [PedestrianGroup](../-pedestrian-group/index.html)<[T](index.html), [V](index.html), [A](index.html)><br>The group this pedestrian belongs to. |
| [shape](index.html#465450099%2FProperties%2F-134779887) | [jvm]<br>abstract val [shape](index.html#465450099%2FProperties%2F-134779887): [GeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape/index.html)<[V](index.html), [A](index.html)> |
| [volatileMemory](index.html#1404294473%2FProperties%2F-134779887) | [jvm]<br>abstract val [volatileMemory](index.html#1404294473%2FProperties%2F-134779887): [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)<[ConvexGeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-convex-geometric-shape/index.html)<[V](index.html), [A](index.html)>, [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)><br>The volatile memory of the agent: it models the ability to remember areas of the environment already visited since the start of the simulation. |


## Inheritors


| Name |
|---|
| [AbstractOrientingPedestrian](../../it.unibo.alchemist.model.implementations.nodes/-abstract-orienting-pedestrian/index.html) |
| [CognitiveOrientingPhysicalPedestrian2D](../../it.unibo.alchemist.model.implementations.nodes/-cognitive-orienting-physical-pedestrian2-d/index.html) |
| [HomogeneousOrientingPhysicalPedestrian2D](../../it.unibo.alchemist.model.implementations.nodes/-homogeneous-orienting-physical-pedestrian2-d/index.html) |

