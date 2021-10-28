//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.nodes](../index.md)/[HomogeneousPhysicalPedestrian2D](index.md)

# HomogeneousPhysicalPedestrian2D

[jvm]\
open class [HomogeneousPhysicalPedestrian2D](index.md)<[T](index.md)>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()constructor(**environment**: [Physics2DEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-physics2-d-environment/index.md)<[T](index.md)>, **randomGenerator**: RandomGenerator, **group**: [PedestrianGroup2D](../../it.unibo.alchemist.model.interfaces/-pedestrian-group2-d/index.md)<[T](index.md)>?) : [HomogeneousPedestrian2D](../-homogeneous-pedestrian2-d/index.md)<[T](index.md)> , [PhysicalPedestrian2D](../../it.unibo.alchemist.model.interfaces/-physical-pedestrian2-d/index.md)<[T](index.md)> 

A homogeneous pedestrian capable of physical interactions, modeled as a [PhysicalPedestrian2D](../../it.unibo.alchemist.model.interfaces/-physical-pedestrian2-d/index.md). [comfortRay](comfort-ray.md) is statically defined to be equal to its [shape](index.md#1628558488%2FProperties%2F-267951372) radius.

## Constructors

| | |
|---|---|
| [HomogeneousPhysicalPedestrian2D](-homogeneous-physical-pedestrian2-d.md) | [jvm]<br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()<br>fun <[T](index.md)> [HomogeneousPhysicalPedestrian2D](-homogeneous-physical-pedestrian2-d.md)(environment: [Physics2DEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-physics2-d-environment/index.md)<[T](index.md)>, randomGenerator: RandomGenerator, group: [PedestrianGroup2D](../../it.unibo.alchemist.model.interfaces/-pedestrian-group2-d/index.md)<[T](index.md)>? = null) |

## Functions

| Name | Summary |
|---|---|
| [addReaction](index.md#-1914162920%2FFunctions%2F-267951372) | [jvm]<br>override fun [addReaction](index.md#-1914162920%2FFunctions%2F-267951372)(p0: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](index.md)>) |
| [cloneNode](index.md#1410251741%2FFunctions%2F-267951372) | [jvm]<br>open override fun [cloneNode](index.md#1410251741%2FFunctions%2F-267951372)(p0: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md)): [AbstractNode](../-abstract-node/index.md)<[T](index.md)> |
| [compareTo](index.md#-635306233%2FFunctions%2F-267951372) | [jvm]<br>operator override fun [compareTo](index.md#-635306233%2FFunctions%2F-267951372)(@NotNull()other: @NotNull()[Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [contains](index.md#-1500024274%2FFunctions%2F-267951372) | [jvm]<br>open operator override fun [contains](index.md#-1500024274%2FFunctions%2F-267951372)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [equals](index.md#1855273807%2FFunctions%2F-267951372) | [jvm]<br>operator override fun [equals](index.md#1855273807%2FFunctions%2F-267951372)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [forEach](index.md#1514566078%2FFunctions%2F-267951372) | [jvm]<br>override fun [forEach](index.md#1514566078%2FFunctions%2F-267951372)(p0: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<in [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](index.md)>>) |
| [getConcentration](index.md#-989109866%2FFunctions%2F-267951372) | [jvm]<br>open override fun [getConcentration](index.md#-989109866%2FFunctions%2F-267951372)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md)): [T](index.md) |
| [getContents](../-abstract-node/get-contents.md) | [jvm]<br>open override fun [getContents](../-abstract-node/get-contents.md)(): [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)<[Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md), [T](index.md)> |
| [getId](index.md#2063123767%2FFunctions%2F-267951372) | [jvm]<br>override fun [getId](index.md#2063123767%2FFunctions%2F-267951372)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getMoleculeCount](../-abstract-node/get-molecule-count.md) | [jvm]<br>open override fun [getMoleculeCount](../-abstract-node/get-molecule-count.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getReactions](index.md#-301186114%2FFunctions%2F-267951372) | [jvm]<br>override fun [getReactions](index.md#-301186114%2FFunctions%2F-267951372)(): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)<[Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](index.md)>> |
| [hashCode](../-abstract-node/hash-code.md) | [jvm]<br>override fun [hashCode](../-abstract-node/hash-code.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [iterator](../-abstract-node/iterator.md) | [jvm]<br>operator override fun [iterator](../-abstract-node/iterator.md)(): [MutableIterator](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-iterator/index.html)<[Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](index.md)>> |
| [physicalForces](../../it.unibo.alchemist.model.interfaces/-physical-pedestrian2-d/index.md#1946949119%2FFunctions%2F-267951372) | [jvm]<br>open override fun [physicalForces](../../it.unibo.alchemist.model.interfaces/-physical-pedestrian2-d/index.md#1946949119%2FFunctions%2F-267951372)(environment: [PhysicsEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment/index.md)<[T](index.md), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md), [Euclidean2DTransformation](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-euclidean2-d-transformation/index.md), [Euclidean2DShapeFactory](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-euclidean2-d-shape-factory/index.md)>): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)> |
| [removeConcentration](index.md#571173562%2FFunctions%2F-267951372) | [jvm]<br>open override fun [removeConcentration](index.md#571173562%2FFunctions%2F-267951372)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md)) |
| [removeReaction](index.md#982079025%2FFunctions%2F-267951372) | [jvm]<br>override fun [removeReaction](index.md#982079025%2FFunctions%2F-267951372)(p0: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](index.md)>) |
| [repulsionForce](../../it.unibo.alchemist.model.interfaces/-physical-pedestrian2-d/repulsion-force.md) | [jvm]<br>open override fun [repulsionForce](../../it.unibo.alchemist.model.interfaces/-physical-pedestrian2-d/repulsion-force.md)(other: [NodeWithShape](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.md)<[T](index.md), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md), *>): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)<br>Computes the repulsion force caused by a node that entered the [comfortArea](../../it.unibo.alchemist.model.interfaces/-physical-pedestrian2-d/comfort-area.md). |
| [setConcentration](index.md#-1479666879%2FFunctions%2F-267951372) | [jvm]<br>open override fun [setConcentration](index.md#-1479666879%2FFunctions%2F-267951372)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md), p1: [T](index.md)) |
| [speed](../-abstract-homogeneous-pedestrian/speed.md) | [jvm]<br>open override fun [speed](../-abstract-homogeneous-pedestrian/speed.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [spliterator](../-abstract-node/spliterator.md) | [jvm]<br>override fun [spliterator](../-abstract-node/spliterator.md)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](index.md)>> |
| [toString](../-abstract-node/to-string.md) | [jvm]<br>open override fun [toString](../-abstract-node/to-string.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

## Properties

| Name | Summary |
|---|---|
| [comfortArea](index.md#1931996608%2FProperties%2F-267951372) | [jvm]<br>open override val [comfortArea](index.md#1931996608%2FProperties%2F-267951372): [Euclidean2DShape](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/index.md#1496739300%2FClasslikes%2F-267951372)<br>The comfort area of this pedestrian, it's a circle of radius [shape](../../it.unibo.alchemist.model.interfaces/-physical-pedestrian2-d/index.md#300387463%2FProperties%2F-267951372). |
| [comfortRay](comfort-ray.md) | [jvm]<br>open override val [comfortRay](comfort-ray.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>The comfort ray of this pedestrian, this is added to the radius of its [shape](index.md#1628558488%2FProperties%2F-267951372) to obtain the [comfortArea](index.md#1931996608%2FProperties%2F-267951372). |
| [environment](index.md#-262815386%2FProperties%2F-267951372) | [jvm]<br>override val [environment](index.md#-262815386%2FProperties%2F-267951372): [Physics2DEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-physics2-d-environment/index.md)<[T](index.md)> |
| [fieldOfView](index.md#-966033885%2FProperties%2F-267951372) | [jvm]<br>override val [fieldOfView](index.md#-966033885%2FProperties%2F-267951372): [FieldOfView2D](../../it.unibo.alchemist.model.implementations.geometry.euclidean2d/-field-of-view2-d/index.md)<[T](index.md)> |
| [membershipGroup](index.md#-587122192%2FProperties%2F-267951372) | [jvm]<br>open override val [membershipGroup](index.md#-587122192%2FProperties%2F-267951372): [PedestrianGroup](../../it.unibo.alchemist.model.interfaces/-pedestrian-group/index.md)<[T](index.md), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md), [Euclidean2DTransformation](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-euclidean2-d-transformation/index.md)> |
| [shape](index.md#1628558488%2FProperties%2F-267951372) | [jvm]<br>open override val [shape](index.md#1628558488%2FProperties%2F-267951372): [Euclidean2DShape](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/index.md#1496739300%2FClasslikes%2F-267951372) |

## Inheritors

| Name |
|---|
| [HomogeneousOrientingPhysicalPedestrian2D](../-homogeneous-orienting-physical-pedestrian2-d/index.md) |
