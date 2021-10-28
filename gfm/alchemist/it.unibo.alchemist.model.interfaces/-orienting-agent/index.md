//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces](../index.md)/[OrientingAgent](index.md)

# OrientingAgent

[jvm]\
interface [OrientingAgent](index.md)<[V](index.md) : [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.md)<[V](index.md)>, [A](index.md) : [GeometricTransformation](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-transformation/index.md)<[V](index.md)>, [L](index.md) : [ConvexGeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-convex-geometric-shape/index.md)<[V](index.md), [A](index.md)>, [R](index.md)>

An agent capable of orienting itself inside an environment.

## Parameters

jvm

| | |
|---|---|
| V | the [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.md) type for the space this agent is inside. |
| A | the transformations supported by the shapes in this space. |
| L | the type of landmarks. See [cognitiveMap](cognitive-map.md). |
| R | the type of edges of the [cognitiveMap](cognitive-map.md), representing the [R](index.md)elations between landmarks. |

## Functions

| Name | Summary |
|---|---|
| [registerVisit](register-visit.md) | [jvm]<br>open fun <[M](register-visit.md) : [ConvexGeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-convex-geometric-shape/index.md)<[V](index.md), [A](index.md)>> [registerVisit](register-visit.md)(area: [M](register-visit.md))<br>Registers a visit to the provided [area](register-visit.md) in the agent's [volatileMemory](volatile-memory.md). |

## Properties

| Name | Summary |
|---|---|
| [cognitiveMap](cognitive-map.md) | [jvm]<br>abstract val [cognitiveMap](cognitive-map.md): [NavigationGraph](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d.graph/-navigation-graph/index.md)<[V](index.md), [A](index.md), [L](index.md), [R](index.md)><br>The cognitive map of the agent. |
| [knowledgeDegree](knowledge-degree.md) | [jvm]<br>abstract val [knowledgeDegree](knowledge-degree.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>The knowledge degree of the agent concerning the environment. |
| [volatileMemory](volatile-memory.md) | [jvm]<br>abstract val [volatileMemory](volatile-memory.md): [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)<[ConvexGeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-convex-geometric-shape/index.md)<[V](index.md), [A](index.md)>, [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)><br>The volatile memory of the agent: it models the ability to remember areas of the environment already visited since the start of the simulation. |

## Inheritors

| Name |
|---|
| [OrientingPedestrian](../-orienting-pedestrian/index.md) |
