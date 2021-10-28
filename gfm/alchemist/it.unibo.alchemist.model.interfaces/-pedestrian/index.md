//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces](../index.md)/[Pedestrian](index.md)

# Pedestrian

[jvm]\
interface [Pedestrian](index.md)<[T](index.md), [S](index.md) : [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.md)<[S](index.md)>, [A](index.md) : [GeometricTransformation](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-transformation/index.md)<[S](index.md)>> : [NodeWithShape](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.md)<[T](index.md), [S](index.md), [A](index.md)> 

A plain pedestrian.

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
| [speed](speed.md) | [jvm]<br>abstract fun [speed](speed.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>The speed at which the pedestrian is moving. |
| [spliterator](../../it.unibo.alchemist.loader.deployments/-close-to-g-p-s-trace/index.md#-1387152138%2FFunctions%2F-267951372) | [jvm]<br>open fun [spliterator](../../it.unibo.alchemist.loader.deployments/-close-to-g-p-s-trace/index.md#-1387152138%2FFunctions%2F-267951372)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[Reaction](../-reaction/index.md)<[T](index.md)>> |

## Properties

| Name | Summary |
|---|---|
| [membershipGroup](membership-group.md) | [jvm]<br>abstract val [membershipGroup](membership-group.md): [PedestrianGroup](../-pedestrian-group/index.md)<[T](index.md), [S](index.md), [A](index.md)><br>The group this pedestrian belongs to. |
| [shape](index.md#-1152302160%2FProperties%2F-267951372) | [jvm]<br>abstract val [shape](index.md#-1152302160%2FProperties%2F-267951372): [GeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape/index.md)<[S](index.md), [A](index.md)> |

## Inheritors

| Name |
|---|
| [AbstractHomogeneousPedestrian](../../it.unibo.alchemist.model.implementations.nodes/-abstract-homogeneous-pedestrian/index.md) |
| [HeterogeneousPedestrian](../-heterogeneous-pedestrian/index.md) |
| [OrientingPedestrian](../-orienting-pedestrian/index.md) |
| [Pedestrian2D](../-pedestrian2-d/index.md) |
| [PhysicalPedestrian](../-physical-pedestrian/index.md) |
