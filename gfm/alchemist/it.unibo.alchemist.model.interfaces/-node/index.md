//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces](../index.md)/[Node](index.md)

# Node

[jvm]\
interface [Node](index.md)<[T](index.md)> : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html), [Iterable](https://docs.oracle.com/javase/8/docs/api/java/lang/Iterable.html)<[Reaction](../-reaction/index.md)<[T](index.md)>> , [Comparable](https://docs.oracle.com/javase/8/docs/api/java/lang/Comparable.html)<[Node](index.md)<[T](index.md)>>

## Parameters

jvm

| | |
|---|---|
| <T> | The type of the concentration This interface must be implemented in every realization of node |

## Functions

| Name | Summary |
|---|---|
| [addReaction](add-reaction.md) | [jvm]<br>abstract fun [addReaction](add-reaction.md)(r: [Reaction](../-reaction/index.md)<[T](index.md)>)<br>Adds a reaction to this node. |
| [cloneNode](clone-node.md) | [jvm]<br>abstract fun [cloneNode](clone-node.md)(currentTime: [Time](../-time/index.md)): [Node](index.md)<[T](index.md)><br>Creates a new Node which is a clone of the current Node. |
| [compareTo](../-g-p-s-point/index.md#-1554281679%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [compareTo](../-g-p-s-point/index.md#-1554281679%2FFunctions%2F-267951372)(p: [T](index.md)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [contains](contains.md) | [jvm]<br>abstract fun [contains](contains.md)(mol: [Molecule](../-molecule/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Tests whether a node contains a [Molecule](../-molecule/index.md). |
| [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-655675525%2FFunctions%2F-267951372) | [jvm]<br>open fun [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-655675525%2FFunctions%2F-267951372)(action: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |
| [getConcentration](get-concentration.md) | [jvm]<br>abstract fun [getConcentration](get-concentration.md)(mol: [Molecule](../-molecule/index.md)): [T](index.md)<br>Calculates the concentration of a molecule. |
| [getContents](get-contents.md) | [jvm]<br>abstract fun [getContents](get-contents.md)(): [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<[Molecule](../-molecule/index.md), [T](index.md)><br>the molecule corresponding to the i-th position |
| [getId](get-id.md) | [jvm]<br>abstract fun [getId](get-id.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>an univocal id for this node in the environment |
| [getMoleculeCount](get-molecule-count.md) | [jvm]<br>abstract fun [getMoleculeCount](get-molecule-count.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>the count of different molecules in this node |
| [getReactions](get-reactions.md) | [jvm]<br>abstract fun [getReactions](get-reactions.md)(): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[Reaction](../-reaction/index.md)<[T](index.md)>><br>This method allows to access all the reaction of the node. |
| [hashCode](hash-code.md) | [jvm]<br>abstract fun [hashCode](hash-code.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [iterator](../../it.unibo.alchemist.loader.variables/-arbitrary-variable/index.md#-1606146105%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [iterator](../../it.unibo.alchemist.loader.variables/-arbitrary-variable/index.md#-1606146105%2FFunctions%2F-267951372)(): [Iterator](https://docs.oracle.com/javase/8/docs/api/java/util/Iterator.html)<[T](index.md)> |
| [removeConcentration](remove-concentration.md) | [jvm]<br>abstract fun [removeConcentration](remove-concentration.md)(mol: [Molecule](../-molecule/index.md))<br>the molecule that should be removed |
| [removeReaction](remove-reaction.md) | [jvm]<br>abstract fun [removeReaction](remove-reaction.md)(r: [Reaction](../-reaction/index.md)<[T](index.md)>)<br>Removes a reaction from this node. |
| [setConcentration](set-concentration.md) | [jvm]<br>abstract fun [setConcentration](set-concentration.md)(mol: [Molecule](../-molecule/index.md), c: [T](index.md))<br>Sets the concentration of mol to c. |
| [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-677603448%2FFunctions%2F-267951372) | [jvm]<br>open fun [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-677603448%2FFunctions%2F-267951372)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[T](index.md)> |

## Inheritors

| Name |
|---|
| [NodeWithShape](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.md) |
| [AbstractNode](../../it.unibo.alchemist.model.implementations.nodes/-abstract-node/index.md) |
| [EnvironmentNode](../-environment-node/index.md) |
| [CellNode](../-cell-node/index.md) |
| [ILsaNode](../-i-lsa-node/index.md) |
