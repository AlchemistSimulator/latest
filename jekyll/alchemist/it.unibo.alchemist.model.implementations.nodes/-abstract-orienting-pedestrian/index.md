---
title: AbstractOrientingPedestrian
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.nodes](../index.html)/[AbstractOrientingPedestrian](index.html)



# AbstractOrientingPedestrian



[jvm]\
abstract class [AbstractOrientingPedestrian](index.html)<[T](index.html), [P](index.html) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<[P](index.html)>, [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html)<[P](index.html)>, [A](index.html) : [GeometricTransformation](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-transformation/index.html)<[P](index.html)>, [L](index.html) : [ConvexGeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-convex-geometric-shape/index.html)<[P](index.html), [A](index.html)>, [N](index.html) : [ConvexGeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-convex-geometric-shape/index.html)<[P](index.html), [A](index.html)>, [E](index.html), [F](index.html) : [GeometricShapeFactory](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape-factory/index.html)<[P](index.html), [A](index.html)>>(**knowledgeDegree**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **randomGenerator**: RandomGenerator, **environment**: [PhysicsEnvironmentWithGraph](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment-with-graph/index.html)<*, [T](index.html), [P](index.html), [A](index.html), [N](index.html), [E](index.html), [F](index.html)>, **group**: [PedestrianGroup](../../it.unibo.alchemist.model.interfaces/-pedestrian-group/index.html)<[T](index.html), [P](index.html), [A](index.html)>?, **minArea**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) : [AbstractHomogeneousPedestrian](../-abstract-homogeneous-pedestrian/index.html)<[T](index.html), [P](index.html), [A](index.html), [F](index.html)> , [OrientingPedestrian](../../it.unibo.alchemist.model.interfaces/-orienting-pedestrian/index.html)<[T](index.html), [P](index.html), [A](index.html), [L](index.html), DefaultEdge> 

An abstract [OrientingPedestrian](../../it.unibo.alchemist.model.interfaces/-orienting-pedestrian/index.html), contains an algorithm for the generation of a pseudo-random [cognitiveMap](cognitive-map.html). The creation of landmarks is left to subclasses via factory method (see createLandmarkIn).



## Parameters


jvm

| | |
|---|---|
| T | the concentration type. |
| P | the [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html) type and [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html) type for the space this pedestrian is inside. |
| A | the transformations supported by the shapes in this space. |
| L | the type of landmarks in the pedestrian's [cognitiveMap](cognitive-map.html). |
| N | the type of nodes of the navigation graph provided by the environment. |
| E | the type of edges of the navigation graph provided by the environment. |
| F | the type of the shape factory provided by the environment. |



## Constructors


| | |
|---|---|
| [AbstractOrientingPedestrian](-abstract-orienting-pedestrian.html) | [jvm]<br>fun <[T](index.html), [P](index.html) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<[P](index.html)>, [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html)<[P](index.html)>, [A](index.html) : [GeometricTransformation](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-transformation/index.html)<[P](index.html)>, [N](index.html) : [ConvexGeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-convex-geometric-shape/index.html)<[P](index.html), [A](index.html)>, [E](index.html), [F](index.html) : [GeometricShapeFactory](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape-factory/index.html)<[P](index.html), [A](index.html)>> [AbstractOrientingPedestrian](-abstract-orienting-pedestrian.html)(knowledgeDegree: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), randomGenerator: RandomGenerator, environment: [PhysicsEnvironmentWithGraph](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment-with-graph/index.html)<*, [T](index.html), [P](index.html), [A](index.html), [N](index.html), [E](index.html), [F](index.html)>, group: [PedestrianGroup](../../it.unibo.alchemist.model.interfaces/-pedestrian-group/index.html)<[T](index.html), [P](index.html), [A](index.html)>? = null, minArea: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 10.0)<br>the concentration type. |


## Functions


| Name | Summary |
|---|---|
| [addReaction](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.html#-1844535178%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [addReaction](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.html#-1844535178%2FFunctions%2F-134779887)(p0: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](index.html)>) |
| [cloneNode](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.html#-144457153%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [cloneNode](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.html#-144457153%2FFunctions%2F-134779887)(p0: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html)): [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](index.html)> |
| [compareTo](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.html#1076068299%2FFunctions%2F-134779887) | [jvm]<br>abstract operator fun [compareTo](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.html#1076068299%2FFunctions%2F-134779887)(other: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](index.html)>): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [contains](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.html#-905365364%2FFunctions%2F-134779887) | [jvm]<br>abstract operator fun [contains](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.html#-905365364%2FFunctions%2F-134779887)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [forEach](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.html#2086990857%2FFunctions%2F-134779887) | [jvm]<br>open fun [forEach](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.html#2086990857%2FFunctions%2F-134779887)(p0: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<in [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](index.html)>>) |
| [getConcentration](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.html#1182263796%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [getConcentration](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.html#1182263796%2FFunctions%2F-134779887)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html)): [T](index.html) |
| [getContents](../../it.unibo.alchemist.model.interfaces/-node/get-contents.html) | [jvm]<br>abstract fun [getContents](../../it.unibo.alchemist.model.interfaces/-node/get-contents.html)(): [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)<[Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html), [T](index.html)> |
| [getId](../../it.unibo.alchemist.model.interfaces/-node/get-id.html) | [jvm]<br>abstract fun [getId](../../it.unibo.alchemist.model.interfaces/-node/get-id.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getMoleculeCount](../../it.unibo.alchemist.model.interfaces/-node/get-molecule-count.html) | [jvm]<br>abstract fun [getMoleculeCount](../../it.unibo.alchemist.model.interfaces/-node/get-molecule-count.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getReactions](../../it.unibo.alchemist.model.interfaces/-node/get-reactions.html) | [jvm]<br>abstract fun [getReactions](../../it.unibo.alchemist.model.interfaces/-node/get-reactions.html)(): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)<[Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](index.html)>> |
| [iterator](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.html#-1651023311%2FFunctions%2F-134779887) | [jvm]<br>abstract operator override fun [iterator](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.html#-1651023311%2FFunctions%2F-134779887)(): [MutableIterator](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-iterator/index.html)<[Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](index.html)>> |
| [registerVisit](index.html#1120265979%2FFunctions%2F-134779887) | [jvm]<br>open fun <[M](index.html#1120265979%2FFunctions%2F-134779887) : [ConvexGeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-convex-geometric-shape/index.html)<[P](index.html), [A](index.html)>> [registerVisit](index.html#1120265979%2FFunctions%2F-134779887)(area: [M](index.html#1120265979%2FFunctions%2F-134779887))<br>Registers a visit to the provided [area](index.html#1120265979%2FFunctions%2F-134779887) in the agent's [volatileMemory](../../it.unibo.alchemist.model.interfaces/-orienting-agent/volatile-memory.html). |
| [removeConcentration](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.html#1461493148%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [removeConcentration](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.html#1461493148%2FFunctions%2F-134779887)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html)) |
| [removeReaction](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.html#792936979%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [removeReaction](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.html#792936979%2FFunctions%2F-134779887)(p0: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](index.html)>) |
| [setConcentration](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.html#1246864287%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [setConcentration](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.html#1246864287%2FFunctions%2F-134779887)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html), p1: [T](index.html)) |
| [speed](../../it.unibo.alchemist.model.interfaces/-pedestrian/speed.html) | [jvm]<br>abstract fun [speed](../../it.unibo.alchemist.model.interfaces/-pedestrian/speed.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>The speed at which the pedestrian is moving. |
| [spliterator](../../it.unibo.alchemist.loader.deployments/-close-to-g-p-s-trace/index.html#-1387152138%2FFunctions%2F-134779887) | [jvm]<br>open fun [spliterator](../../it.unibo.alchemist.loader.deployments/-close-to-g-p-s-trace/index.html#-1387152138%2FFunctions%2F-134779887)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](index.html)>> |


## Properties


| Name | Summary |
|---|---|
| [cognitiveMap](cognitive-map.html) | [jvm]<br>open override val [cognitiveMap](cognitive-map.html): [NavigationGraph](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d.graph/-navigation-graph/index.html)<[P](index.html), [A](index.html), [L](index.html), DefaultEdge><br>The cognitive map of the pedestrian. |
| [environment](index.html#322801955%2FProperties%2F-134779887) | [jvm]<br>open val [environment](index.html#322801955%2FProperties%2F-134779887): [PhysicsEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment/index.html)<[T](index.html), [P](index.html), [A](index.html), [F](index.html)><br>    the environment inside which this pedestrian moves. |
| [knowledgeDegree](knowledge-degree.html) | [jvm]<br>override val [knowledgeDegree](knowledge-degree.html): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>The knowledge degree of the agent concerning the environment. |
| [membershipGroup](index.html#-1546591443%2FProperties%2F-134779887) | [jvm]<br>abstract val [membershipGroup](index.html#-1546591443%2FProperties%2F-134779887): [PedestrianGroup](../../it.unibo.alchemist.model.interfaces/-pedestrian-group/index.html)<[T](index.html), [P](index.html), [A](index.html)><br>The group this pedestrian belongs to. |
| [shape](index.html#51082773%2FProperties%2F-134779887) | [jvm]<br>abstract val [shape](index.html#51082773%2FProperties%2F-134779887): [GeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape/index.html)<[P](index.html), [A](index.html)> |
| [volatileMemory](volatile-memory.html) | [jvm]<br>open override val [volatileMemory](volatile-memory.html): [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)<[ConvexGeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-convex-geometric-shape/index.html)<[P](index.html), [A](index.html)>, [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)><br>The volatile memory of the agent: it models the ability to remember areas of the environment already visited since the start of the simulation. |


## Inheritors


| Name |
|---|
| [HomogeneousOrientingPedestrian2D](../-homogeneous-orienting-pedestrian2-d/index.html) |

