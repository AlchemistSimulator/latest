---
title: AbstractNode
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.nodes](../index.html)/[AbstractNode](index.html)



# AbstractNode



[jvm]\
abstract class [AbstractNode](index.html)<[T](index.html)> : [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist/-supported-incarnations/get.html)> 

This class realizes an abstract node. You may extend it to realize your own nodes.



## Parameters


jvm

| | |
|---|---|
| <T> | concentration type |



## Constructors


| | |
|---|---|
| [AbstractNode](-abstract-node.html) | [jvm]<br>open fun [AbstractNode](-abstract-node.html)(env: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>)<br>the environment, used to generate sequential ids for each environment, always starting from 0. |


## Functions


| Name | Summary |
|---|---|
| [addReaction](add-reaction.html) | [jvm]<br>fun [addReaction](add-reaction.html)(reactionToAdd: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist/-supported-incarnations/get.html)>) |
| [cloneNode](clone-node.html) | [jvm]<br>open fun [cloneNode](clone-node.html)(currentTime: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html)): [AbstractNode](index.html)<[T](../../it.unibo.alchemist/-supported-incarnations/get.html)><br>Default implementation fails: override correctly calling the constructor. |
| [compareTo](compare-to.html) | [jvm]<br>fun [compareTo](compare-to.html)(@NotNull()other: @NotNull()[Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist/-supported-incarnations/get.html)>): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [contains](contains.html) | [jvm]<br>open fun [contains](contains.html)(molecule: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [equals](equals.html) | [jvm]<br>fun [equals](equals.html)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [forEach](for-each.html) | [jvm]<br>fun [forEach](for-each.html)(action: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |
| [getConcentration](get-concentration.html) | [jvm]<br>open fun [getConcentration](get-concentration.html)(molecule: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html)): [T](../../it.unibo.alchemist/-supported-incarnations/get.html) |
| [getContents](get-contents.html) | [jvm]<br>open fun [getContents](get-contents.html)(): [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<[Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html), [T](../../it.unibo.alchemist/-supported-incarnations/get.html)> |
| [getId](../../it.unibo.alchemist.model.interfaces/-node/get-id.html) | [jvm]<br>abstract fun [getId](../../it.unibo.alchemist.model.interfaces/-node/get-id.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getMoleculeCount](get-molecule-count.html) | [jvm]<br>open fun [getMoleculeCount](get-molecule-count.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getReactions](../../it.unibo.alchemist.model.interfaces/-node/get-reactions.html) | [jvm]<br>abstract fun [getReactions](../../it.unibo.alchemist.model.interfaces/-node/get-reactions.html)(): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist/-supported-incarnations/get.html)>> |
| [hashCode](hash-code.html) | [jvm]<br>fun [hashCode](hash-code.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [iterator](iterator.html) | [jvm]<br>fun [iterator](iterator.html)(): [Iterator](https://docs.oracle.com/javase/8/docs/api/java/util/Iterator.html)<[Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist/-supported-incarnations/get.html)>> |
| [removeConcentration](remove-concentration.html) | [jvm]<br>open fun [removeConcentration](remove-concentration.html)(moleculeToRemove: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html)) |
| [removeReaction](remove-reaction.html) | [jvm]<br>fun [removeReaction](remove-reaction.html)(reactionToRemove: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist/-supported-incarnations/get.html)>) |
| [setConcentration](set-concentration.html) | [jvm]<br>open fun [setConcentration](set-concentration.html)(molecule: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html), concentration: [T](../../it.unibo.alchemist/-supported-incarnations/get.html)) |
| [spliterator](spliterator.html) | [jvm]<br>fun [spliterator](spliterator.html)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist/-supported-incarnations/get.html)>> |
| [toString](to-string.html) | [jvm]<br>open fun [toString](to-string.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |


## Properties


| Name | Summary |
|---|---|
| [id](id.html) | [jvm]<br>private val [id](id.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [reactions](reactions.html) | [jvm]<br>private val [reactions](reactions.html): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist/-supported-incarnations/get.html)>> |


## Inheritors


| Name |
|---|
| [AbstractHomogeneousPedestrian](../-abstract-homogeneous-pedestrian/index.html) |
| [CircleNode](../-circle-node/index.html) |
| [IntNode](../-int-node/index.html) |
| [IntegerNode](../-integer-node/index.html) |
| [DoubleNode](../-double-node/index.html) |
| [ProtelisNode](../-protelis-node/index.html) |
| [LsaNode](../-lsa-node/index.html) |

