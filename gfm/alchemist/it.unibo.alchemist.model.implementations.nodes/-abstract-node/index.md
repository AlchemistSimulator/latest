//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.nodes](../index.md)/[AbstractNode](index.md)

# AbstractNode

[jvm]\
abstract class [AbstractNode](index.md)<[T](index.md)> : [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-interact-with-others/index.md)> 

This class realizes an abstract node. You may extend it to realize your own nodes.

## Parameters

jvm

| | |
|---|---|
| <T> | concentration type |

## Constructors

| | |
|---|---|
| [AbstractNode](-abstract-node.md) | [jvm]<br>open fun [AbstractNode](-abstract-node.md)(env: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>)<br>the environment, used to generate sequential ids for each environment, always starting from 0. |

## Functions

| Name | Summary |
|---|---|
| [addReaction](add-reaction.md) | [jvm]<br>fun [addReaction](add-reaction.md)(reactionToAdd: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-interact-with-others/index.md)>) |
| [cloneNode](clone-node.md) | [jvm]<br>open fun [cloneNode](clone-node.md)(currentTime: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md)): [AbstractNode](index.md)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-interact-with-others/index.md)><br>Default implementation fails: override correctly calling the constructor. |
| [compareTo](compare-to.md) | [jvm]<br>fun [compareTo](compare-to.md)(@NotNull()other: @NotNull()[Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-interact-with-others/index.md)>): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [contains](contains.md) | [jvm]<br>open fun [contains](contains.md)(molecule: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [equals](equals.md) | [jvm]<br>fun [equals](equals.md)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [forEach](for-each.md) | [jvm]<br>fun [forEach](for-each.md)(action: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |
| [getConcentration](get-concentration.md) | [jvm]<br>open fun [getConcentration](get-concentration.md)(molecule: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md)): [T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-interact-with-others/index.md) |
| [getContents](get-contents.md) | [jvm]<br>open fun [getContents](get-contents.md)(): [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<[Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md), [T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-interact-with-others/index.md)> |
| [getId](../../it.unibo.alchemist.model.interfaces/-node/get-id.md) | [jvm]<br>abstract fun [getId](../../it.unibo.alchemist.model.interfaces/-node/get-id.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getMoleculeCount](get-molecule-count.md) | [jvm]<br>open fun [getMoleculeCount](get-molecule-count.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getReactions](../../it.unibo.alchemist.model.interfaces/-node/get-reactions.md) | [jvm]<br>abstract fun [getReactions](../../it.unibo.alchemist.model.interfaces/-node/get-reactions.md)(): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-interact-with-others/index.md)>> |
| [hashCode](hash-code.md) | [jvm]<br>fun [hashCode](hash-code.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [iterator](iterator.md) | [jvm]<br>fun [iterator](iterator.md)(): [Iterator](https://docs.oracle.com/javase/8/docs/api/java/util/Iterator.html)<[Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-interact-with-others/index.md)>> |
| [removeConcentration](remove-concentration.md) | [jvm]<br>open fun [removeConcentration](remove-concentration.md)(moleculeToRemove: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md)) |
| [removeReaction](remove-reaction.md) | [jvm]<br>fun [removeReaction](remove-reaction.md)(reactionToRemove: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-interact-with-others/index.md)>) |
| [setConcentration](set-concentration.md) | [jvm]<br>open fun [setConcentration](set-concentration.md)(molecule: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md), concentration: [T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-interact-with-others/index.md)) |
| [spliterator](spliterator.md) | [jvm]<br>fun [spliterator](spliterator.md)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-interact-with-others/index.md)>> |
| [toString](to-string.md) | [jvm]<br>open fun [toString](to-string.md)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |

## Properties

| Name | Summary |
|---|---|
| [id](id.md) | [jvm]<br>private val [id](id.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [reactions](reactions.md) | [jvm]<br>private val [reactions](reactions.md): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-interact-with-others/index.md)>> |

## Inheritors

| Name |
|---|
| [AbstractHomogeneousPedestrian](../-abstract-homogeneous-pedestrian/index.md) |
| [CircleNode](../-circle-node/index.md) |
| [IntNode](../-int-node/index.md) |
| [IntegerNode](../-integer-node/index.md) |
| [DoubleNode](../-double-node/index.md) |
| [ProtelisNode](../-protelis-node/index.md) |
| [LsaNode](../-lsa-node/index.md) |
