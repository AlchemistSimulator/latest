---
title: OrientingAgent
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces](../index.html)/[OrientingAgent](index.html)



# OrientingAgent



[jvm]\
interface [OrientingAgent](index.html)<[V](index.html) : [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html)<[V](index.html)>, [A](index.html) : [GeometricTransformation](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-transformation/index.html)<[V](index.html)>, [L](index.html) : [ConvexGeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-convex-geometric-shape/index.html)<[V](index.html), [A](index.html)>, [R](index.html)>

An agent capable of orienting itself inside an environment.



## Parameters


jvm

| | |
|---|---|
| V | the [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html) type for the space this agent is inside. |
| A | the transformations supported by the shapes in this space. |
| L | the type of landmarks. See [cognitiveMap](cognitive-map.html). |
| R | the type of edges of the [cognitiveMap](cognitive-map.html), representing the [R](index.html)elations between landmarks. |



## Functions


| Name | Summary |
|---|---|
| [registerVisit](register-visit.html) | [jvm]<br>open fun <[M](register-visit.html) : [ConvexGeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-convex-geometric-shape/index.html)<[V](index.html), [A](index.html)>> [registerVisit](register-visit.html)(area: [M](register-visit.html))<br>Registers a visit to the provided [area](register-visit.html) in the agent's [volatileMemory](volatile-memory.html). |


## Properties


| Name | Summary |
|---|---|
| [cognitiveMap](cognitive-map.html) | [jvm]<br>abstract val [cognitiveMap](cognitive-map.html): [NavigationGraph](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d.graph/-navigation-graph/index.html)<[V](index.html), [A](index.html), [L](index.html), [R](index.html)><br>The cognitive map of the agent. |
| [knowledgeDegree](knowledge-degree.html) | [jvm]<br>abstract val [knowledgeDegree](knowledge-degree.html): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>The knowledge degree of the agent concerning the environment. |
| [volatileMemory](volatile-memory.html) | [jvm]<br>abstract val [volatileMemory](volatile-memory.html): [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)<[ConvexGeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-convex-geometric-shape/index.html)<[V](index.html), [A](index.html)>, [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)><br>The volatile memory of the agent: it models the ability to remember areas of the environment already visited since the start of the simulation. |


## Inheritors


| Name |
|---|
| [OrientingPedestrian](../-orienting-pedestrian/index.html) |

