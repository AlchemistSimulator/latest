//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces](../index.md)/[Pedestrian2D](index.md)

# Pedestrian2D

[jvm]\
interface [Pedestrian2D](index.md)<[T](index.md)> : [Pedestrian](../-pedestrian/index.md)<[T](index.md), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md), [Euclidean2DTransformation](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-euclidean2-d-transformation/index.md)> 

A bidimensional pedestrian.

## Types

| Name | Summary |
|---|---|
| [Companion](-companion/index.md) | [jvm]<br>object [Companion](-companion/index.md) |

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
| [removeConcentration](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.md#1461493148%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [removeConcentration](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.md#1461493148%2FFunctions%2F-267951372)(p0: [Molecule](../-molecule/index.md)) |
| [removeReaction](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.md#792936979%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [removeReaction](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.md#792936979%2FFunctions%2F-267951372)(p0: [Reaction](../-reaction/index.md)<[T](index.md)>) |
| [setConcentration](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.md#1246864287%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [setConcentration](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.md#1246864287%2FFunctions%2F-267951372)(p0: [Molecule](../-molecule/index.md), p1: [T](index.md)) |
| [speed](../-pedestrian/speed.md) | [jvm]<br>abstract fun [speed](../-pedestrian/speed.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>The speed at which the pedestrian is moving. |
| [spliterator](../../it.unibo.alchemist.loader.deployments/-close-to-g-p-s-trace/index.md#-1387152138%2FFunctions%2F-267951372) | [jvm]<br>open fun [spliterator](../../it.unibo.alchemist.loader.deployments/-close-to-g-p-s-trace/index.md#-1387152138%2FFunctions%2F-267951372)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[Reaction](../-reaction/index.md)<[T](index.md)>> |

## Properties

| Name | Summary |
|---|---|
| [environment](environment.md) | [jvm]<br>abstract val [environment](environment.md): [Physics2DEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-physics2-d-environment/index.md)<[T](index.md)><br>Access to the [environment](environment.md). |
| [fieldOfView](field-of-view.md) | [jvm]<br>open val [fieldOfView](field-of-view.md): [FieldOfView2D](../../it.unibo.alchemist.model.implementations.geometry.euclidean2d/-field-of-view2-d/index.md)<[T](index.md)><br>The field of view of a pedestrian in the Euclidean world. |
| [membershipGroup](index.md#1580002230%2FProperties%2F-267951372) | [jvm]<br>abstract val [membershipGroup](index.md#1580002230%2FProperties%2F-267951372): [PedestrianGroup](../-pedestrian-group/index.md)<[T](index.md), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md), [Euclidean2DTransformation](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-euclidean2-d-transformation/index.md)><br>The group this pedestrian belongs to. |
| [shape](shape.md) | [jvm]<br>open override val [shape](shape.md): [Euclidean2DShape](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/index.md#1496739300%2FClasslikes%2F-267951372)<br>The shape of any pedestrian in the Euclidean world. |

## Inheritors

| Name |
|---|
| [CognitivePedestrian2D](../../it.unibo.alchemist.model.implementations.nodes/-cognitive-pedestrian2-d/index.md) |
| [HeterogeneousPedestrian2D](../../it.unibo.alchemist.model.implementations.nodes/-heterogeneous-pedestrian2-d/index.md) |
| [HomogeneousOrientingPedestrian2D](../../it.unibo.alchemist.model.implementations.nodes/-homogeneous-orienting-pedestrian2-d/index.md) |
| [HomogeneousPedestrian2D](../../it.unibo.alchemist.model.implementations.nodes/-homogeneous-pedestrian2-d/index.md) |
| [PhysicalPedestrian2D](../-physical-pedestrian2-d/index.md) |
