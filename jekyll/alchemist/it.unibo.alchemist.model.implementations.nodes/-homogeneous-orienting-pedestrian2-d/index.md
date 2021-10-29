---
title: HomogeneousOrientingPedestrian2D
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.nodes](../index.html)/[HomogeneousOrientingPedestrian2D](index.html)



# HomogeneousOrientingPedestrian2D



[jvm]\
open class [HomogeneousOrientingPedestrian2D](index.html)<[T](index.html), [N](index.html) : [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.html), [E](index.html)>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()constructor(**environment**: [EuclideanPhysics2DEnvironmentWithGraph](../../it.unibo.alchemist.model.interfaces.environments/-euclidean-physics2-d-environment-with-graph/index.html)<*, [T](index.html), [N](index.html), [E](index.html)>, **randomGenerator**: RandomGenerator, **knowledgeDegree**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **minSide**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **maxSide**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **group**: [PedestrianGroup2D](../../it.unibo.alchemist.model.interfaces/-pedestrian-group2-d/index.html)<[T](index.html)>?) : [AbstractOrientingPedestrian](../-abstract-orienting-pedestrian/index.html)<[T](index.html), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html), [Euclidean2DTransformation](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-euclidean2-d-transformation/index.html), [Ellipse](../../it.unibo.alchemist.model.implementations.geometry.euclidean2d/-ellipse/index.html), [N](index.html), [E](index.html), [Euclidean2DShapeFactory](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-euclidean2-d-shape-factory/index.html)> , [Pedestrian2D](../../it.unibo.alchemist.model.interfaces/-pedestrian2-d/index.html)<[T](index.html)> 

A homogeneous [OrientingPedestrian](../../it.unibo.alchemist.model.interfaces/-orienting-pedestrian/index.html) in the Euclidean world. Landmarks are represented as [Ellipse](../../it.unibo.alchemist.model.implementations.geometry.euclidean2d/-ellipse/index.html)s, which can model the human error concerning both the exact position of a landmark and the angles formed by the connections between them. This class accepts an environment whose graph contains [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.html)al nodes.



## Parameters


jvm

| | |
|---|---|
| T | the concentration type. |
| N | the type of nodes of the navigation graph provided by the environment. |
| E | the type of edges of the navigation graph provided by the environment. |



## Constructors


| | |
|---|---|
| [HomogeneousOrientingPedestrian2D](-homogeneous-orienting-pedestrian2-d.html) | [jvm]<br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()<br>fun <[T](index.html), [N](index.html) : [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.html), [E](index.html)> [HomogeneousOrientingPedestrian2D](-homogeneous-orienting-pedestrian2-d.html)(environment: [EuclideanPhysics2DEnvironmentWithGraph](../../it.unibo.alchemist.model.interfaces.environments/-euclidean-physics2-d-environment-with-graph/index.html)<*, [T](index.html), [N](index.html), [E](index.html)>, randomGenerator: RandomGenerator, knowledgeDegree: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), minSide: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 30.0, maxSide: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 60.0, group: [PedestrianGroup2D](../../it.unibo.alchemist.model.interfaces/-pedestrian-group2-d/index.html)<[T](index.html)>? = null)<br>the concentration type. |


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
| [registerVisit](../-homogeneous-orienting-physical-pedestrian2-d/index.html#1721887883%2FFunctions%2F-134779887) | [jvm]<br>open fun <[M](../-homogeneous-orienting-physical-pedestrian2-d/index.html#1721887883%2FFunctions%2F-134779887) : [ConvexGeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-convex-geometric-shape/index.html)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html), [Euclidean2DTransformation](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-euclidean2-d-transformation/index.html)>> [registerVisit](../-homogeneous-orienting-physical-pedestrian2-d/index.html#1721887883%2FFunctions%2F-134779887)(area: [M](../-homogeneous-orienting-physical-pedestrian2-d/index.html#1721887883%2FFunctions%2F-134779887))<br>Registers a visit to the provided [area](../-homogeneous-orienting-physical-pedestrian2-d/index.html#1721887883%2FFunctions%2F-134779887) in the agent's [volatileMemory](../../it.unibo.alchemist.model.interfaces/-orienting-agent/volatile-memory.html). |
| [removeConcentration](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.html#1461493148%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [removeConcentration](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.html#1461493148%2FFunctions%2F-134779887)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html)) |
| [removeReaction](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.html#792936979%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [removeReaction](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.html#792936979%2FFunctions%2F-134779887)(p0: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](index.html)>) |
| [setConcentration](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.html#1246864287%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [setConcentration](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.html#1246864287%2FFunctions%2F-134779887)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html), p1: [T](index.html)) |
| [speed](../../it.unibo.alchemist.model.interfaces/-pedestrian/speed.html) | [jvm]<br>abstract fun [speed](../../it.unibo.alchemist.model.interfaces/-pedestrian/speed.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>The speed at which the pedestrian is moving. |
| [spliterator](../../it.unibo.alchemist.loader.deployments/-close-to-g-p-s-trace/index.html#-1387152138%2FFunctions%2F-134779887) | [jvm]<br>open fun [spliterator](../../it.unibo.alchemist.loader.deployments/-close-to-g-p-s-trace/index.html#-1387152138%2FFunctions%2F-134779887)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](index.html)>> |


## Properties


| Name | Summary |
|---|---|
| [cognitiveMap](index.html#-1287567065%2FProperties%2F-134779887) | [jvm]<br>open override val [cognitiveMap](index.html#-1287567065%2FProperties%2F-134779887): [NavigationGraph](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d.graph/-navigation-graph/index.html)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html), [Euclidean2DTransformation](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-euclidean2-d-transformation/index.html), [Ellipse](../../it.unibo.alchemist.model.implementations.geometry.euclidean2d/-ellipse/index.html), DefaultEdge><br>The cognitive map of the pedestrian. |
| [environment](environment.html) | [jvm]<br>open override val [environment](environment.html): [EuclideanPhysics2DEnvironmentWithGraph](../../it.unibo.alchemist.model.interfaces.environments/-euclidean-physics2-d-environment-with-graph/index.html)<*, [T](index.html), [N](index.html), [E](index.html)><br>    the environment inside which this pedestrian moves. |
| [fieldOfView](field-of-view.html) | [jvm]<br>override val [fieldOfView](field-of-view.html): [FieldOfView2D](../../it.unibo.alchemist.model.implementations.geometry.euclidean2d/-field-of-view2-d/index.html)<[T](index.html)><br>The field of view of a pedestrian in the Euclidean world. |
| [knowledgeDegree](index.html#1320473031%2FProperties%2F-134779887) | [jvm]<br>override val [knowledgeDegree](index.html#1320473031%2FProperties%2F-134779887): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>The knowledge degree of the agent concerning the environment. |
| [membershipGroup](index.html#-328957112%2FProperties%2F-134779887) | [jvm]<br>abstract val [membershipGroup](index.html#-328957112%2FProperties%2F-134779887): [PedestrianGroup](../../it.unibo.alchemist.model.interfaces/-pedestrian-group/index.html)<[T](index.html), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html), [Euclidean2DTransformation](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-euclidean2-d-transformation/index.html)><br>The group this pedestrian belongs to. |
| [shape](shape.html) | [jvm]<br>open override val [shape](shape.html): [GeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape/index.html)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html), [Euclidean2DTransformation](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-euclidean2-d-transformation/index.html)><br>The shape of any pedestrian in the Euclidean world. |
| [volatileMemory](index.html#502512236%2FProperties%2F-134779887) | [jvm]<br>open override val [volatileMemory](index.html#502512236%2FProperties%2F-134779887): [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)<[ConvexGeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-convex-geometric-shape/index.html)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html), [Euclidean2DTransformation](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-euclidean2-d-transformation/index.html)>, [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)><br>The volatile memory of the agent: it models the ability to remember areas of the environment already visited since the start of the simulation. |


## Inheritors


| Name |
|---|
| [CognitiveOrientingPedestrian2D](../-cognitive-orienting-pedestrian2-d/index.html) |

