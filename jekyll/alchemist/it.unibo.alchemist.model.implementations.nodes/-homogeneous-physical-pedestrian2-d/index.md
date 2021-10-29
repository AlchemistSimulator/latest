---
title: HomogeneousPhysicalPedestrian2D
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.nodes](../index.html)/[HomogeneousPhysicalPedestrian2D](index.html)



# HomogeneousPhysicalPedestrian2D



[jvm]\
open class [HomogeneousPhysicalPedestrian2D](index.html)<[T](index.html)>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()constructor(**environment**: [Physics2DEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-physics2-d-environment/index.html)<[T](index.html)>, **randomGenerator**: RandomGenerator, **group**: [PedestrianGroup2D](../../it.unibo.alchemist.model.interfaces/-pedestrian-group2-d/index.html)<[T](index.html)>?) : [HomogeneousPedestrian2D](../-homogeneous-pedestrian2-d/index.html)<[T](index.html)> , [PhysicalPedestrian2D](../../it.unibo.alchemist.model.interfaces/-physical-pedestrian2-d/index.html)<[T](index.html)> 

A homogeneous pedestrian capable of physical interactions, modeled as a [PhysicalPedestrian2D](../../it.unibo.alchemist.model.interfaces/-physical-pedestrian2-d/index.html). [comfortRay](comfort-ray.html) is statically defined to be equal to its [shape](index.html#1628558488%2FProperties%2F-134779887) radius.



## Constructors


| | |
|---|---|
| [HomogeneousPhysicalPedestrian2D](-homogeneous-physical-pedestrian2-d.html) | [jvm]<br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()<br>fun <[T](index.html)> [HomogeneousPhysicalPedestrian2D](-homogeneous-physical-pedestrian2-d.html)(environment: [Physics2DEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-physics2-d-environment/index.html)<[T](index.html)>, randomGenerator: RandomGenerator, group: [PedestrianGroup2D](../../it.unibo.alchemist.model.interfaces/-pedestrian-group2-d/index.html)<[T](index.html)>? = null) |


## Functions


| Name | Summary |
|---|---|
| [addReaction](index.html#-1914162920%2FFunctions%2F-134779887) | [jvm]<br>override fun [addReaction](index.html#-1914162920%2FFunctions%2F-134779887)(p0: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](index.html)>) |
| [cloneNode](index.html#1410251741%2FFunctions%2F-134779887) | [jvm]<br>open override fun [cloneNode](index.html#1410251741%2FFunctions%2F-134779887)(p0: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html)): [AbstractNode](../-abstract-node/index.html)<[T](index.html)> |
| [compareTo](index.html#-635306233%2FFunctions%2F-134779887) | [jvm]<br>operator override fun [compareTo](index.html#-635306233%2FFunctions%2F-134779887)(@NotNull()other: @NotNull()[Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](index.html)>): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [contains](index.html#-1500024274%2FFunctions%2F-134779887) | [jvm]<br>open operator override fun [contains](index.html#-1500024274%2FFunctions%2F-134779887)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [equals](index.html#1855273807%2FFunctions%2F-134779887) | [jvm]<br>operator override fun [equals](index.html#1855273807%2FFunctions%2F-134779887)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [forEach](index.html#1514566078%2FFunctions%2F-134779887) | [jvm]<br>override fun [forEach](index.html#1514566078%2FFunctions%2F-134779887)(p0: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<in [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](index.html)>>) |
| [getConcentration](index.html#-989109866%2FFunctions%2F-134779887) | [jvm]<br>open override fun [getConcentration](index.html#-989109866%2FFunctions%2F-134779887)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html)): [T](index.html) |
| [getContents](../-abstract-node/get-contents.html) | [jvm]<br>open override fun [getContents](../-abstract-node/get-contents.html)(): [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)<[Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html), [T](index.html)> |
| [getId](index.html#2063123767%2FFunctions%2F-134779887) | [jvm]<br>override fun [getId](index.html#2063123767%2FFunctions%2F-134779887)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getMoleculeCount](../-abstract-node/get-molecule-count.html) | [jvm]<br>open override fun [getMoleculeCount](../-abstract-node/get-molecule-count.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getReactions](index.html#-301186114%2FFunctions%2F-134779887) | [jvm]<br>override fun [getReactions](index.html#-301186114%2FFunctions%2F-134779887)(): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)<[Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](index.html)>> |
| [hashCode](../-abstract-node/hash-code.html) | [jvm]<br>override fun [hashCode](../-abstract-node/hash-code.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [iterator](../-abstract-node/iterator.html) | [jvm]<br>operator override fun [iterator](../-abstract-node/iterator.html)(): [MutableIterator](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-iterator/index.html)<[Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](index.html)>> |
| [physicalForces](../../it.unibo.alchemist.model.interfaces/-physical-pedestrian2-d/index.html#1946949119%2FFunctions%2F-134779887) | [jvm]<br>open override fun [physicalForces](../../it.unibo.alchemist.model.interfaces/-physical-pedestrian2-d/index.html#1946949119%2FFunctions%2F-134779887)(environment: [PhysicsEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment/index.html)<[T](index.html), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html), [Euclidean2DTransformation](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-euclidean2-d-transformation/index.html), [Euclidean2DShapeFactory](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-euclidean2-d-shape-factory/index.html)>): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)> |
| [removeConcentration](index.html#571173562%2FFunctions%2F-134779887) | [jvm]<br>open override fun [removeConcentration](index.html#571173562%2FFunctions%2F-134779887)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html)) |
| [removeReaction](index.html#982079025%2FFunctions%2F-134779887) | [jvm]<br>override fun [removeReaction](index.html#982079025%2FFunctions%2F-134779887)(p0: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](index.html)>) |
| [repulsionForce](../../it.unibo.alchemist.model.interfaces/-physical-pedestrian2-d/repulsion-force.html) | [jvm]<br>open override fun [repulsionForce](../../it.unibo.alchemist.model.interfaces/-physical-pedestrian2-d/repulsion-force.html)(other: [NodeWithShape](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.html)<[T](index.html), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html), *>): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)<br>Computes the repulsion force caused by a node that entered the [comfortArea](../../it.unibo.alchemist.model.interfaces/-physical-pedestrian2-d/comfort-area.html). |
| [setConcentration](index.html#-1479666879%2FFunctions%2F-134779887) | [jvm]<br>open override fun [setConcentration](index.html#-1479666879%2FFunctions%2F-134779887)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html), p1: [T](index.html)) |
| [speed](../-abstract-homogeneous-pedestrian/speed.html) | [jvm]<br>open override fun [speed](../-abstract-homogeneous-pedestrian/speed.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [spliterator](../-abstract-node/spliterator.html) | [jvm]<br>override fun [spliterator](../-abstract-node/spliterator.html)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](index.html)>> |
| [toString](../-abstract-node/to-string.html) | [jvm]<br>open override fun [toString](../-abstract-node/to-string.html)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |


## Properties


| Name | Summary |
|---|---|
| [comfortArea](index.html#1931996608%2FProperties%2F-134779887) | [jvm]<br>open override val [comfortArea](index.html#1931996608%2FProperties%2F-134779887): [Euclidean2DShape](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/index.html#1496739300%2FClasslikes%2F-134779887)<br>The comfort area of this pedestrian, it's a circle of radius [shape](../../it.unibo.alchemist.model.interfaces/-physical-pedestrian2-d/index.html#300387463%2FProperties%2F-134779887). |
| [comfortRay](comfort-ray.html) | [jvm]<br>open override val [comfortRay](comfort-ray.html): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>The comfort ray of this pedestrian, this is added to the radius of its [shape](index.html#1628558488%2FProperties%2F-134779887) to obtain the [comfortArea](index.html#1931996608%2FProperties%2F-134779887). |
| [environment](index.html#-262815386%2FProperties%2F-134779887) | [jvm]<br>override val [environment](index.html#-262815386%2FProperties%2F-134779887): [Physics2DEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-physics2-d-environment/index.html)<[T](index.html)> |
| [fieldOfView](index.html#-966033885%2FProperties%2F-134779887) | [jvm]<br>override val [fieldOfView](index.html#-966033885%2FProperties%2F-134779887): [FieldOfView2D](../../it.unibo.alchemist.model.implementations.geometry.euclidean2d/-field-of-view2-d/index.html)<[T](index.html)> |
| [membershipGroup](index.html#-587122192%2FProperties%2F-134779887) | [jvm]<br>open override val [membershipGroup](index.html#-587122192%2FProperties%2F-134779887): [PedestrianGroup](../../it.unibo.alchemist.model.interfaces/-pedestrian-group/index.html)<[T](index.html), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html), [Euclidean2DTransformation](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-euclidean2-d-transformation/index.html)> |
| [shape](index.html#1628558488%2FProperties%2F-134779887) | [jvm]<br>open override val [shape](index.html#1628558488%2FProperties%2F-134779887): [Euclidean2DShape](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/index.html#1496739300%2FClasslikes%2F-134779887) |


## Inheritors


| Name |
|---|
| [HomogeneousOrientingPhysicalPedestrian2D](../-homogeneous-orienting-physical-pedestrian2-d/index.html) |

