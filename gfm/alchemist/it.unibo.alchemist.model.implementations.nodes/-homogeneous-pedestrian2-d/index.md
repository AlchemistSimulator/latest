//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.nodes](../index.md)/[HomogeneousPedestrian2D](index.md)

# HomogeneousPedestrian2D

[jvm]\
open class [HomogeneousPedestrian2D](index.md)<[T](index.md)>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()constructor(**environment**: [Physics2DEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-physics2-d-environment/index.md)<[T](index.md)>, **randomGenerator**: RandomGenerator, **group**: [PedestrianGroup2D](../../it.unibo.alchemist.model.interfaces/-pedestrian-group2-d/index.md)<[T](index.md)>?) : [AbstractHomogeneousPedestrian](../-abstract-homogeneous-pedestrian/index.md)<[T](index.md), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md), [Euclidean2DTransformation](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-euclidean2-d-transformation/index.md), [Euclidean2DShapeFactory](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-euclidean2-d-shape-factory/index.md)> , [Pedestrian2D](../../it.unibo.alchemist.model.interfaces/-pedestrian2-d/index.md)<[T](index.md)> 

Implementation of a homogeneous pedestrian in the Euclidean world.

## Parameters

jvm

| | |
|---|---|
| environment | the environment inside which this pedestrian moves. |
| randomGenerator | the simulation {@link RandomGenerator}. |

## Constructors

| | |
|---|---|
| [HomogeneousPedestrian2D](-homogeneous-pedestrian2-d.md) | [jvm]<br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()<br>fun <[T](index.md)> [HomogeneousPedestrian2D](-homogeneous-pedestrian2-d.md)(environment: [Physics2DEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-physics2-d-environment/index.md)<[T](index.md)>, randomGenerator: RandomGenerator, group: [PedestrianGroup2D](../../it.unibo.alchemist.model.interfaces/-pedestrian-group2-d/index.md)<[T](index.md)>? = null)<br>    the environment inside which this pedestrian moves. |

## Functions

| Name | Summary |
|---|---|
| [addReaction](../-homogeneous-physical-pedestrian2-d/index.md#-1914162920%2FFunctions%2F-267951372) | [jvm]<br>override fun [addReaction](../-homogeneous-physical-pedestrian2-d/index.md#-1914162920%2FFunctions%2F-267951372)(p0: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](index.md)>) |
| [cloneNode](../-homogeneous-physical-pedestrian2-d/index.md#1410251741%2FFunctions%2F-267951372) | [jvm]<br>open override fun [cloneNode](../-homogeneous-physical-pedestrian2-d/index.md#1410251741%2FFunctions%2F-267951372)(p0: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md)): [AbstractNode](../-abstract-node/index.md)<[T](index.md)> |
| [compareTo](../-homogeneous-physical-pedestrian2-d/index.md#-635306233%2FFunctions%2F-267951372) | [jvm]<br>operator override fun [compareTo](../-homogeneous-physical-pedestrian2-d/index.md#-635306233%2FFunctions%2F-267951372)(@NotNull()other: @NotNull()[Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [contains](../-homogeneous-physical-pedestrian2-d/index.md#-1500024274%2FFunctions%2F-267951372) | [jvm]<br>open operator override fun [contains](../-homogeneous-physical-pedestrian2-d/index.md#-1500024274%2FFunctions%2F-267951372)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [equals](../-homogeneous-physical-pedestrian2-d/index.md#1855273807%2FFunctions%2F-267951372) | [jvm]<br>operator override fun [equals](../-homogeneous-physical-pedestrian2-d/index.md#1855273807%2FFunctions%2F-267951372)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [forEach](../-homogeneous-physical-pedestrian2-d/index.md#1514566078%2FFunctions%2F-267951372) | [jvm]<br>override fun [forEach](../-homogeneous-physical-pedestrian2-d/index.md#1514566078%2FFunctions%2F-267951372)(p0: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<in [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](index.md)>>) |
| [getConcentration](../-homogeneous-physical-pedestrian2-d/index.md#-989109866%2FFunctions%2F-267951372) | [jvm]<br>open override fun [getConcentration](../-homogeneous-physical-pedestrian2-d/index.md#-989109866%2FFunctions%2F-267951372)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md)): [T](index.md) |
| [getContents](../-abstract-node/get-contents.md) | [jvm]<br>open override fun [getContents](../-abstract-node/get-contents.md)(): [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)<[Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md), [T](index.md)> |
| [getId](../-homogeneous-physical-pedestrian2-d/index.md#2063123767%2FFunctions%2F-267951372) | [jvm]<br>override fun [getId](../-homogeneous-physical-pedestrian2-d/index.md#2063123767%2FFunctions%2F-267951372)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getMoleculeCount](../-abstract-node/get-molecule-count.md) | [jvm]<br>open override fun [getMoleculeCount](../-abstract-node/get-molecule-count.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getReactions](../-homogeneous-physical-pedestrian2-d/index.md#-301186114%2FFunctions%2F-267951372) | [jvm]<br>override fun [getReactions](../-homogeneous-physical-pedestrian2-d/index.md#-301186114%2FFunctions%2F-267951372)(): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)<[Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](index.md)>> |
| [hashCode](../-abstract-node/hash-code.md) | [jvm]<br>override fun [hashCode](../-abstract-node/hash-code.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [iterator](../-abstract-node/iterator.md) | [jvm]<br>operator override fun [iterator](../-abstract-node/iterator.md)(): [MutableIterator](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-iterator/index.html)<[Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](index.md)>> |
| [removeConcentration](../-homogeneous-physical-pedestrian2-d/index.md#571173562%2FFunctions%2F-267951372) | [jvm]<br>open override fun [removeConcentration](../-homogeneous-physical-pedestrian2-d/index.md#571173562%2FFunctions%2F-267951372)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md)) |
| [removeReaction](../-homogeneous-physical-pedestrian2-d/index.md#982079025%2FFunctions%2F-267951372) | [jvm]<br>override fun [removeReaction](../-homogeneous-physical-pedestrian2-d/index.md#982079025%2FFunctions%2F-267951372)(p0: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](index.md)>) |
| [setConcentration](../-homogeneous-physical-pedestrian2-d/index.md#-1479666879%2FFunctions%2F-267951372) | [jvm]<br>open override fun [setConcentration](../-homogeneous-physical-pedestrian2-d/index.md#-1479666879%2FFunctions%2F-267951372)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md), p1: [T](index.md)) |
| [speed](../-abstract-homogeneous-pedestrian/speed.md) | [jvm]<br>open override fun [speed](../-abstract-homogeneous-pedestrian/speed.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>The speed at which the pedestrian is moving. |
| [spliterator](../-abstract-node/spliterator.md) | [jvm]<br>override fun [spliterator](../-abstract-node/spliterator.md)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](index.md)>> |
| [toString](../-abstract-node/to-string.md) | [jvm]<br>open override fun [toString](../-abstract-node/to-string.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

## Properties

| Name | Summary |
|---|---|
| [environment](environment.md) | [jvm]<br>override val [environment](environment.md): [Physics2DEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-physics2-d-environment/index.md)<[T](index.md)><br>    the environment inside which this pedestrian moves. |
| [fieldOfView](field-of-view.md) | [jvm]<br>override val [fieldOfView](field-of-view.md): [FieldOfView2D](../../it.unibo.alchemist.model.implementations.geometry.euclidean2d/-field-of-view2-d/index.md)<[T](index.md)><br>The field of view of a pedestrian in the Euclidean world. |
| [membershipGroup](index.md#-1947896953%2FProperties%2F-267951372) | [jvm]<br>open override val [membershipGroup](index.md#-1947896953%2FProperties%2F-267951372): [PedestrianGroup](../../it.unibo.alchemist.model.interfaces/-pedestrian-group/index.md)<[T](index.md), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md), [Euclidean2DTransformation](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-euclidean2-d-transformation/index.md)><br>The group this pedestrian belongs to. |
| [shape](shape.md) | [jvm]<br>open override val [shape](shape.md): [GeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape/index.md)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md), [Euclidean2DTransformation](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-euclidean2-d-transformation/index.md)><br>The shape of any pedestrian in the Euclidean world. |

## Inheritors

| Name |
|---|
| [HomogeneousPhysicalPedestrian2D](../-homogeneous-physical-pedestrian2-d/index.md) |
