---
title: HeterogeneousPedestrian
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces](../index.html)/[HeterogeneousPedestrian](index.html)



# HeterogeneousPedestrian



[jvm]\
interface [HeterogeneousPedestrian](index.html)<[T](index.html), [S](index.html) : [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html)<[S](index.html)>, [A](index.html) : [GeometricTransformation](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-transformation/index.html)<[S](index.html)>> : [Pedestrian](../-pedestrian/index.html)<[T](index.html), [S](index.html), [A](index.html)> 

A pedestrian with individual characteristics.



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
| [probabilityOfHelping](probability-of-helping.html) | [jvm]<br>abstract fun [probabilityOfHelping](probability-of-helping.html)(toHelp: [HeterogeneousPedestrian](index.html)<[T](index.html), [S](index.html), [A](index.html)>): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Value between 0 and 1 representing the probability this pedestrian will help another pedestrian in difficulty. |
| [removeConcentration](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.html#1461493148%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [removeConcentration](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.html#1461493148%2FFunctions%2F-134779887)(p0: [Molecule](../-molecule/index.html)) |
| [removeReaction](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.html#792936979%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [removeReaction](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.html#792936979%2FFunctions%2F-134779887)(p0: [Reaction](../-reaction/index.html)<[T](index.html)>) |
| [setConcentration](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.html#1246864287%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [setConcentration](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.html#1246864287%2FFunctions%2F-134779887)(p0: [Molecule](../-molecule/index.html), p1: [T](index.html)) |
| [speed](../-pedestrian/speed.html) | [jvm]<br>abstract fun [speed](../-pedestrian/speed.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>The speed at which the pedestrian is moving. |
| [spliterator](../../it.unibo.alchemist.loader.deployments/-close-to-g-p-s-trace/index.html#-1387152138%2FFunctions%2F-134779887) | [jvm]<br>open fun [spliterator](../../it.unibo.alchemist.loader.deployments/-close-to-g-p-s-trace/index.html#-1387152138%2FFunctions%2F-134779887)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[Reaction](../-reaction/index.html)<[T](index.html)>> |


## Properties


| Name | Summary |
|---|---|
| [age](age.html) | [jvm]<br>abstract val [age](age.html): [Age](../../it.unibo.alchemist.model.cognitiveagents.impact.individual/-age/index.html)<br>The age of this pedestrian. |
| [compliance](compliance.html) | [jvm]<br>abstract val [compliance](compliance.html): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Value between 0 and 1 representing the attitude towards conforming to social rules of this pedestrian. |
| [gender](gender.html) | [jvm]<br>abstract val [gender](gender.html): [Gender](../../it.unibo.alchemist.model.cognitiveagents.impact.individual/-gender/index.html)<br>The gender of this pedestrian. |
| [membershipGroup](index.html#749066427%2FProperties%2F-134779887) | [jvm]<br>abstract val [membershipGroup](index.html#749066427%2FProperties%2F-134779887): [PedestrianGroup](../-pedestrian-group/index.html)<[T](index.html), [S](index.html), [A](index.html)><br>The group this pedestrian belongs to. |
| [shape](index.html#-843225821%2FProperties%2F-134779887) | [jvm]<br>abstract val [shape](index.html#-843225821%2FProperties%2F-134779887): [GeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape/index.html)<[S](index.html), [A](index.html)> |


## Inheritors


| Name |
|---|
| [AbstractHeterogeneousPedestrian](../../it.unibo.alchemist.model.implementations.nodes/-abstract-heterogeneous-pedestrian/index.html) |
| [CognitivePedestrian](../-cognitive-pedestrian/index.html) |

