//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces.nodes](../index.md)/[NodeWithShape](index.md)

# NodeWithShape

[jvm]\
interface [NodeWithShape](index.md)<[T](index.md), [S](index.md) : [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.md)<[S](index.md)>, [A](index.md) : [GeometricTransformation](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-transformation/index.md)<[S](index.md)>> : [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)> 

A node with a [shape](shape.md).

## Functions

| Name | Summary |
|---|---|
| [addReaction](index.md#-1844535178%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [addReaction](index.md#-1844535178%2FFunctions%2F-267951372)(p0: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](index.md)>) |
| [cloneNode](index.md#-144457153%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [cloneNode](index.md#-144457153%2FFunctions%2F-267951372)(p0: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md)): [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)> |
| [compareTo](index.md#1076068299%2FFunctions%2F-267951372) | [jvm]<br>abstract operator fun [compareTo](index.md#1076068299%2FFunctions%2F-267951372)(other: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [contains](index.md#-905365364%2FFunctions%2F-267951372) | [jvm]<br>abstract operator fun [contains](index.md#-905365364%2FFunctions%2F-267951372)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [forEach](index.md#2086990857%2FFunctions%2F-267951372) | [jvm]<br>open fun [forEach](index.md#2086990857%2FFunctions%2F-267951372)(p0: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<in [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](index.md)>>) |
| [getConcentration](index.md#1182263796%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [getConcentration](index.md#1182263796%2FFunctions%2F-267951372)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md)): [T](index.md) |
| [getContents](../../it.unibo.alchemist.model.interfaces/-node/get-contents.md) | [jvm]<br>abstract fun [getContents](../../it.unibo.alchemist.model.interfaces/-node/get-contents.md)(): [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)<[Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md), [T](index.md)> |
| [getId](../../it.unibo.alchemist.model.interfaces/-node/get-id.md) | [jvm]<br>abstract fun [getId](../../it.unibo.alchemist.model.interfaces/-node/get-id.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getMoleculeCount](../../it.unibo.alchemist.model.interfaces/-node/get-molecule-count.md) | [jvm]<br>abstract fun [getMoleculeCount](../../it.unibo.alchemist.model.interfaces/-node/get-molecule-count.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getReactions](../../it.unibo.alchemist.model.interfaces/-node/get-reactions.md) | [jvm]<br>abstract fun [getReactions](../../it.unibo.alchemist.model.interfaces/-node/get-reactions.md)(): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)<[Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](index.md)>> |
| [iterator](index.md#-1651023311%2FFunctions%2F-267951372) | [jvm]<br>abstract operator override fun [iterator](index.md#-1651023311%2FFunctions%2F-267951372)(): [MutableIterator](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-iterator/index.html)<[Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](index.md)>> |
| [removeConcentration](index.md#1461493148%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [removeConcentration](index.md#1461493148%2FFunctions%2F-267951372)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md)) |
| [removeReaction](index.md#792936979%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [removeReaction](index.md#792936979%2FFunctions%2F-267951372)(p0: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](index.md)>) |
| [setConcentration](index.md#1246864287%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [setConcentration](index.md#1246864287%2FFunctions%2F-267951372)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md), p1: [T](index.md)) |
| [spliterator](../../it.unibo.alchemist.loader.deployments/-close-to-g-p-s-trace/index.md#-1387152138%2FFunctions%2F-267951372) | [jvm]<br>open fun [spliterator](../../it.unibo.alchemist.loader.deployments/-close-to-g-p-s-trace/index.md#-1387152138%2FFunctions%2F-267951372)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](index.md)>> |

## Properties

| Name | Summary |
|---|---|
| [shape](shape.md) | [jvm]<br>abstract val [shape](shape.md): [GeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape/index.md)<[S](index.md), [A](index.md)><br>The shape of the node. |

## Inheritors

| Name |
|---|
| [Pedestrian](../../it.unibo.alchemist.model.interfaces/-pedestrian/index.md) |
| [CircleNode](../../it.unibo.alchemist.model.implementations.nodes/-circle-node/index.md) |
| [PhysicalNode](../../it.unibo.alchemist.model.interfaces/-physical-node/index.md) |
