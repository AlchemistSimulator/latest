---
title: NodeWithShape
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces.nodes](../index.html)/[NodeWithShape](index.html)



# NodeWithShape



[jvm]\
interface [NodeWithShape](index.html)<[T](index.html), [S](index.html) : [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html)<[S](index.html)>, [A](index.html) : [GeometricTransformation](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-transformation/index.html)<[S](index.html)>> : [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](index.html)> 

A node with a [shape](shape.html).



## Functions


| Name | Summary |
|---|---|
| [addReaction](index.html#-1844535178%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [addReaction](index.html#-1844535178%2FFunctions%2F-134779887)(p0: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](index.html)>) |
| [cloneNode](index.html#-144457153%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [cloneNode](index.html#-144457153%2FFunctions%2F-134779887)(p0: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html)): [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](index.html)> |
| [compareTo](index.html#1076068299%2FFunctions%2F-134779887) | [jvm]<br>abstract operator fun [compareTo](index.html#1076068299%2FFunctions%2F-134779887)(other: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](index.html)>): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [contains](index.html#-905365364%2FFunctions%2F-134779887) | [jvm]<br>abstract operator fun [contains](index.html#-905365364%2FFunctions%2F-134779887)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [forEach](index.html#2086990857%2FFunctions%2F-134779887) | [jvm]<br>open fun [forEach](index.html#2086990857%2FFunctions%2F-134779887)(p0: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<in [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](index.html)>>) |
| [getConcentration](index.html#1182263796%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [getConcentration](index.html#1182263796%2FFunctions%2F-134779887)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html)): [T](index.html) |
| [getContents](../../it.unibo.alchemist.model.interfaces/-node/get-contents.html) | [jvm]<br>abstract fun [getContents](../../it.unibo.alchemist.model.interfaces/-node/get-contents.html)(): [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)<[Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html), [T](index.html)> |
| [getId](../../it.unibo.alchemist.model.interfaces/-node/get-id.html) | [jvm]<br>abstract fun [getId](../../it.unibo.alchemist.model.interfaces/-node/get-id.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getMoleculeCount](../../it.unibo.alchemist.model.interfaces/-node/get-molecule-count.html) | [jvm]<br>abstract fun [getMoleculeCount](../../it.unibo.alchemist.model.interfaces/-node/get-molecule-count.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getReactions](../../it.unibo.alchemist.model.interfaces/-node/get-reactions.html) | [jvm]<br>abstract fun [getReactions](../../it.unibo.alchemist.model.interfaces/-node/get-reactions.html)(): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)<[Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](index.html)>> |
| [iterator](index.html#-1651023311%2FFunctions%2F-134779887) | [jvm]<br>abstract operator override fun [iterator](index.html#-1651023311%2FFunctions%2F-134779887)(): [MutableIterator](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-iterator/index.html)<[Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](index.html)>> |
| [removeConcentration](index.html#1461493148%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [removeConcentration](index.html#1461493148%2FFunctions%2F-134779887)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html)) |
| [removeReaction](index.html#792936979%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [removeReaction](index.html#792936979%2FFunctions%2F-134779887)(p0: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](index.html)>) |
| [setConcentration](index.html#1246864287%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [setConcentration](index.html#1246864287%2FFunctions%2F-134779887)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html), p1: [T](index.html)) |
| [spliterator](../../it.unibo.alchemist.loader.deployments/-close-to-g-p-s-trace/index.html#-1387152138%2FFunctions%2F-134779887) | [jvm]<br>open fun [spliterator](../../it.unibo.alchemist.loader.deployments/-close-to-g-p-s-trace/index.html#-1387152138%2FFunctions%2F-134779887)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](index.html)>> |


## Properties


| Name | Summary |
|---|---|
| [shape](shape.html) | [jvm]<br>abstract val [shape](shape.html): [GeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape/index.html)<[S](index.html), [A](index.html)><br>The shape of the node. |


## Inheritors


| Name |
|---|
| [Pedestrian](../../it.unibo.alchemist.model.interfaces/-pedestrian/index.html) |
| [CircleNode](../../it.unibo.alchemist.model.implementations.nodes/-circle-node/index.html) |
| [PhysicalNode](../../it.unibo.alchemist.model.interfaces/-physical-node/index.html) |

