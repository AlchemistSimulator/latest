//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces](../index.md)/[OrientingPedestrian](index.md)

# OrientingPedestrian

[jvm]\
interface [OrientingPedestrian](index.md)<[T](index.md), [V](index.md) : [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.md)<[V](index.md)>, [A](index.md) : [GeometricTransformation](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-transformation/index.md)<[V](index.md)>, [L](index.md) : [ConvexGeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-convex-geometric-shape/index.md)<[V](index.md), [A](index.md)>, [R](index.md)> : [Pedestrian](../-pedestrian/index.md)<[T](index.md), [V](index.md), [A](index.md)> , [OrientingAgent](../-orienting-agent/index.md)<[V](index.md), [A](index.md), [L](index.md), [R](index.md)> 

A pedestrian capable of orienting itself.

## Parameters

jvm

| | |
|---|---|
| T | the concentration type. |
| V | the [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.md) type for the space this pedestrian is inside. |
| A | the transformations supported by the shapes in this space. |
| L | the type of landmarks stored in the pedestrian's [cognitiveMap](index.md#286553924%2FProperties%2F-267951372). |
| R | the type of edges of the [cognitiveMap](index.md#286553924%2FProperties%2F-267951372), representing the [R](index.md)elations between landmarks. |

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
| [iterator](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.md#-1651023311%2FFunctions%2F-267951372) | [jvm]<br>abstract operator override fun [iterator](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.md#-1651023311%2FFunctions%2F-267951372)(): [MutableIterator](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-iterator/index.html)<[Reaction](../-reaction/index.md)<[T](index.md)>> |
| [registerVisit](../-orienting-agent/register-visit.md) | [jvm]<br>open fun <[M](../-orienting-agent/register-visit.md) : [ConvexGeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-convex-geometric-shape/index.md)<[V](index.md), [A](index.md)>> [registerVisit](../-orienting-agent/register-visit.md)(area: [M](../-orienting-agent/register-visit.md))<br>Registers a visit to the provided [area](../-orienting-agent/register-visit.md) in the agent's [volatileMemory](../-orienting-agent/volatile-memory.md). |
| [removeConcentration](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.md#1461493148%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [removeConcentration](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.md#1461493148%2FFunctions%2F-267951372)(p0: [Molecule](../-molecule/index.md)) |
| [removeReaction](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.md#792936979%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [removeReaction](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.md#792936979%2FFunctions%2F-267951372)(p0: [Reaction](../-reaction/index.md)<[T](index.md)>) |
| [setConcentration](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.md#1246864287%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [setConcentration](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.md#1246864287%2FFunctions%2F-267951372)(p0: [Molecule](../-molecule/index.md), p1: [T](index.md)) |
| [speed](../-pedestrian/speed.md) | [jvm]<br>abstract fun [speed](../-pedestrian/speed.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>The speed at which the pedestrian is moving. |
| [spliterator](../../it.unibo.alchemist.loader.deployments/-close-to-g-p-s-trace/index.md#-1387152138%2FFunctions%2F-267951372) | [jvm]<br>open fun [spliterator](../../it.unibo.alchemist.loader.deployments/-close-to-g-p-s-trace/index.md#-1387152138%2FFunctions%2F-267951372)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[Reaction](../-reaction/index.md)<[T](index.md)>> |

## Properties

| Name | Summary |
|---|---|
| [cognitiveMap](index.md#286553924%2FProperties%2F-267951372) | [jvm]<br>abstract val [cognitiveMap](index.md#286553924%2FProperties%2F-267951372): [NavigationGraph](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d.graph/-navigation-graph/index.md)<[V](index.md), [A](index.md), [L](index.md), [R](index.md)><br>The cognitive map of the agent. |
| [knowledgeDegree](index.md#-789048694%2FProperties%2F-267951372) | [jvm]<br>abstract val [knowledgeDegree](index.md#-789048694%2FProperties%2F-267951372): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>The knowledge degree of the agent concerning the environment. |
| [membershipGroup](index.md#1856488459%2FProperties%2F-267951372) | [jvm]<br>abstract val [membershipGroup](index.md#1856488459%2FProperties%2F-267951372): [PedestrianGroup](../-pedestrian-group/index.md)<[T](index.md), [V](index.md), [A](index.md)><br>The group this pedestrian belongs to. |
| [shape](index.md#465450099%2FProperties%2F-267951372) | [jvm]<br>abstract val [shape](index.md#465450099%2FProperties%2F-267951372): [GeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape/index.md)<[V](index.md), [A](index.md)> |
| [volatileMemory](index.md#1404294473%2FProperties%2F-267951372) | [jvm]<br>abstract val [volatileMemory](index.md#1404294473%2FProperties%2F-267951372): [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)<[ConvexGeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-convex-geometric-shape/index.md)<[V](index.md), [A](index.md)>, [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)><br>The volatile memory of the agent: it models the ability to remember areas of the environment already visited since the start of the simulation. |

## Inheritors

| Name |
|---|
| [AbstractOrientingPedestrian](../../it.unibo.alchemist.model.implementations.nodes/-abstract-orienting-pedestrian/index.md) |
| [CognitiveOrientingPhysicalPedestrian2D](../../it.unibo.alchemist.model.implementations.nodes/-cognitive-orienting-physical-pedestrian2-d/index.md) |
| [HomogeneousOrientingPhysicalPedestrian2D](../../it.unibo.alchemist.model.implementations.nodes/-homogeneous-orienting-physical-pedestrian2-d/index.md) |
