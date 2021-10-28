---
title: PhysicalPedestrian2D
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces](../index.html)/[PhysicalPedestrian2D](index.html)



# PhysicalPedestrian2D



[jvm]\
interface [PhysicalPedestrian2D](index.html)<[T](index.html)> : [PhysicalPedestrian](../-physical-pedestrian/index.html)<[T](index.html), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html), [Euclidean2DTransformation](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-euclidean2-d-transformation/index.html), [Euclidean2DShapeFactory](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-euclidean2-d-shape-factory/index.html)> , [Pedestrian2D](../-pedestrian2-d/index.html)<[T](index.html)> 

A [PhysicalPedestrian](../-physical-pedestrian/index.html) in an euclidean bidimensional space. This pedestrian has a circular [comfortArea](comfort-area.html) of radius equal to its shape radius plus a [comfortRay](comfort-ray.html). This is derived from [the work of Pelechano et al](https://bit.ly/3e3C7Tb).



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
| [physicalForces](index.html#1946949119%2FFunctions%2F-134779887) | [jvm]<br>open override fun [physicalForces](index.html#1946949119%2FFunctions%2F-134779887)(environment: [PhysicsEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment/index.html)<[T](index.html), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html), [Euclidean2DTransformation](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-euclidean2-d-transformation/index.html), [Euclidean2DShapeFactory](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-euclidean2-d-shape-factory/index.html)>): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)> |
| [removeConcentration](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.html#1461493148%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [removeConcentration](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.html#1461493148%2FFunctions%2F-134779887)(p0: [Molecule](../-molecule/index.html)) |
| [removeReaction](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.html#792936979%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [removeReaction](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.html#792936979%2FFunctions%2F-134779887)(p0: [Reaction](../-reaction/index.html)<[T](index.html)>) |
| [repulsionForce](repulsion-force.html) | [jvm]<br>open override fun [repulsionForce](repulsion-force.html)(other: [NodeWithShape](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.html)<[T](index.html), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html), *>): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)<br>Computes the repulsion force caused by a node that entered the [comfortArea](comfort-area.html). |
| [setConcentration](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.html#1246864287%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [setConcentration](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.html#1246864287%2FFunctions%2F-134779887)(p0: [Molecule](../-molecule/index.html), p1: [T](index.html)) |
| [speed](../-pedestrian/speed.html) | [jvm]<br>abstract fun [speed](../-pedestrian/speed.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [spliterator](../../it.unibo.alchemist.loader.deployments/-close-to-g-p-s-trace/index.html#-1387152138%2FFunctions%2F-134779887) | [jvm]<br>open fun [spliterator](../../it.unibo.alchemist.loader.deployments/-close-to-g-p-s-trace/index.html#-1387152138%2FFunctions%2F-134779887)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[Reaction](../-reaction/index.html)<[T](index.html)>> |


## Properties


| Name | Summary |
|---|---|
| [comfortArea](comfort-area.html) | [jvm]<br>open override val [comfortArea](comfort-area.html): [Euclidean2DShape](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/index.html#1496739300%2FClasslikes%2F-134779887)<br>The comfort area of this pedestrian, it's a circle of radius [shape](index.html#300387463%2FProperties%2F-134779887). |
| [comfortRay](comfort-ray.html) | [jvm]<br>abstract val [comfortRay](comfort-ray.html): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>The comfort ray of this pedestrian, this is added to the radius of its [shape](index.html#300387463%2FProperties%2F-134779887) to obtain the [comfortArea](comfort-area.html). |
| [environment](index.html#-457733611%2FProperties%2F-134779887) | [jvm]<br>abstract val [environment](index.html#-457733611%2FProperties%2F-134779887): [Physics2DEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-physics2-d-environment/index.html)<[T](index.html)> |
| [fieldOfView](index.html#-1160952110%2FProperties%2F-134779887) | [jvm]<br>open val [fieldOfView](index.html#-1160952110%2FProperties%2F-134779887): [FieldOfView2D](../../it.unibo.alchemist.model.implementations.geometry.euclidean2d/-field-of-view2-d/index.html)<[T](index.html)> |
| [membershipGroup](index.html#-991882465%2FProperties%2F-134779887) | [jvm]<br>abstract val [membershipGroup](index.html#-991882465%2FProperties%2F-134779887): [PedestrianGroup](../-pedestrian-group/index.html)<[T](index.html), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html), [Euclidean2DTransformation](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-euclidean2-d-transformation/index.html)> |
| [shape](index.html#300387463%2FProperties%2F-134779887) | [jvm]<br>abstract val [shape](index.html#300387463%2FProperties%2F-134779887): [GeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape/index.html)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html), [Euclidean2DTransformation](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-euclidean2-d-transformation/index.html)> |


## Inheritors


| Name |
|---|
| [CognitivePhysicalPedestrian2D](../../it.unibo.alchemist.model.implementations.nodes/-cognitive-physical-pedestrian2-d/index.html) |
| [HomogeneousPhysicalPedestrian2D](../../it.unibo.alchemist.model.implementations.nodes/-homogeneous-physical-pedestrian2-d/index.html) |

