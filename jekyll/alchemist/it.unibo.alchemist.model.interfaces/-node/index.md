---
title: Node
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces](../index.html)/[Node](index.html)



# Node



[jvm]\
interface [Node](index.html)<[T](index.html)> : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html), [Iterable](https://docs.oracle.com/javase/8/docs/api/java/lang/Iterable.html)<[Reaction](../-reaction/index.html)<[T](index.html)>> , [Comparable](https://docs.oracle.com/javase/8/docs/api/java/lang/Comparable.html)<[Node](index.html)<[T](index.html)>>



## Parameters


jvm

| | |
|---|---|
| <T> | The type of the concentration This interface must be implemented in every realization of node |



## Functions


| Name | Summary |
|---|---|
| [addReaction](add-reaction.html) | [jvm]<br>abstract fun [addReaction](add-reaction.html)(r: [Reaction](../-reaction/index.html)<[T](index.html)>)<br>Adds a reaction to this node. |
| [cloneNode](clone-node.html) | [jvm]<br>abstract fun [cloneNode](clone-node.html)(currentTime: [Time](../-time/index.html)): [Node](index.html)<[T](index.html)><br>Creates a new Node which is a clone of the current Node. |
| [compareTo](../-g-p-s-point/index.html#-1554281679%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [compareTo](../-g-p-s-point/index.html#-1554281679%2FFunctions%2F-134779887)(p: [T](index.html)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [contains](contains.html) | [jvm]<br>abstract fun [contains](contains.html)(mol: [Molecule](../-molecule/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Tests whether a node contains a [Molecule](../-molecule/index.html). |
| [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-655675525%2FFunctions%2F-134779887) | [jvm]<br>open fun [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-655675525%2FFunctions%2F-134779887)(action: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |
| [getConcentration](get-concentration.html) | [jvm]<br>abstract fun [getConcentration](get-concentration.html)(mol: [Molecule](../-molecule/index.html)): [T](index.html)<br>Calculates the concentration of a molecule. |
| [getContents](get-contents.html) | [jvm]<br>abstract fun [getContents](get-contents.html)(): [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<[Molecule](../-molecule/index.html), [T](index.html)><br>the molecule corresponding to the i-th position |
| [getId](get-id.html) | [jvm]<br>abstract fun [getId](get-id.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>an univocal id for this node in the environment |
| [getMoleculeCount](get-molecule-count.html) | [jvm]<br>abstract fun [getMoleculeCount](get-molecule-count.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>the count of different molecules in this node |
| [getReactions](get-reactions.html) | [jvm]<br>abstract fun [getReactions](get-reactions.html)(): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[Reaction](../-reaction/index.html)<[T](index.html)>><br>This method allows to access all the reaction of the node. |
| [hashCode](hash-code.html) | [jvm]<br>abstract fun [hashCode](hash-code.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [iterator](../../it.unibo.alchemist.loader.variables/-arbitrary-variable/index.html#-1606146105%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [iterator](../../it.unibo.alchemist.loader.variables/-arbitrary-variable/index.html#-1606146105%2FFunctions%2F-134779887)(): [Iterator](https://docs.oracle.com/javase/8/docs/api/java/util/Iterator.html)<[T](index.html)> |
| [removeConcentration](remove-concentration.html) | [jvm]<br>abstract fun [removeConcentration](remove-concentration.html)(mol: [Molecule](../-molecule/index.html))<br>the molecule that should be removed |
| [removeReaction](remove-reaction.html) | [jvm]<br>abstract fun [removeReaction](remove-reaction.html)(r: [Reaction](../-reaction/index.html)<[T](index.html)>)<br>Removes a reaction from this node. |
| [setConcentration](set-concentration.html) | [jvm]<br>abstract fun [setConcentration](set-concentration.html)(mol: [Molecule](../-molecule/index.html), c: [T](index.html))<br>Sets the concentration of mol to c. |
| [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-677603448%2FFunctions%2F-134779887) | [jvm]<br>open fun [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-677603448%2FFunctions%2F-134779887)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[T](index.html)> |


## Inheritors


| Name |
|---|
| [NodeWithShape](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.html) |
| [AbstractNode](../../it.unibo.alchemist.model.implementations.nodes/-abstract-node/index.html) |
| [EnvironmentNode](../-environment-node/index.html) |
| [CellNode](../-cell-node/index.html) |
| [ILsaNode](../-i-lsa-node/index.html) |

