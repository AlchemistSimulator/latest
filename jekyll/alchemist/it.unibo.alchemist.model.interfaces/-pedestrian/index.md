---
title: Pedestrian
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces](../index.html)/[Pedestrian](index.html)



# Pedestrian



[jvm]\
interface [Pedestrian](index.html)<[T](index.html), [S](index.html) : [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html)<[S](index.html)>, [A](index.html) : [GeometricTransformation](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-transformation/index.html)<[S](index.html)>> : [NodeWithShape](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.html)<[T](index.html), [S](index.html), [A](index.html)> 

A plain pedestrian.



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
| [removeConcentration](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.html#1461493148%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [removeConcentration](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.html#1461493148%2FFunctions%2F-134779887)(p0: [Molecule](../-molecule/index.html)) |
| [removeReaction](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.html#792936979%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [removeReaction](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.html#792936979%2FFunctions%2F-134779887)(p0: [Reaction](../-reaction/index.html)<[T](index.html)>) |
| [setConcentration](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.html#1246864287%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [setConcentration](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.html#1246864287%2FFunctions%2F-134779887)(p0: [Molecule](../-molecule/index.html), p1: [T](index.html)) |
| [speed](speed.html) | [jvm]<br>abstract fun [speed](speed.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>The speed at which the pedestrian is moving. |
| [spliterator](../../it.unibo.alchemist.loader.deployments/-close-to-g-p-s-trace/index.html#-1387152138%2FFunctions%2F-134779887) | [jvm]<br>open fun [spliterator](../../it.unibo.alchemist.loader.deployments/-close-to-g-p-s-trace/index.html#-1387152138%2FFunctions%2F-134779887)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[Reaction](../-reaction/index.html)<[T](index.html)>> |


## Properties


| Name | Summary |
|---|---|
| [membershipGroup](membership-group.html) | [jvm]<br>abstract val [membershipGroup](membership-group.html): [PedestrianGroup](../-pedestrian-group/index.html)<[T](index.html), [S](index.html), [A](index.html)><br>The group this pedestrian belongs to. |
| [shape](index.html#-1152302160%2FProperties%2F-134779887) | [jvm]<br>abstract val [shape](index.html#-1152302160%2FProperties%2F-134779887): [GeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape/index.html)<[S](index.html), [A](index.html)> |


## Inheritors


| Name |
|---|
| [AbstractHomogeneousPedestrian](../../it.unibo.alchemist.model.implementations.nodes/-abstract-homogeneous-pedestrian/index.html) |
| [HeterogeneousPedestrian](../-heterogeneous-pedestrian/index.html) |
| [OrientingPedestrian](../-orienting-pedestrian/index.html) |
| [Pedestrian2D](../-pedestrian2-d/index.html) |
| [PhysicalPedestrian](../-physical-pedestrian/index.html) |
