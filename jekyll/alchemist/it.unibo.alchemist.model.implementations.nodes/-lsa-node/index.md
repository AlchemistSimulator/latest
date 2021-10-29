---
title: LsaNode
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.nodes](../index.html)/[LsaNode](index.html)



# LsaNode



[jvm]\
class [LsaNode](index.html) : [AbstractNode](../-abstract-node/index.html)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html)>> , [ILsaNode](../../it.unibo.alchemist.model.interfaces/-i-lsa-node/index.html)

This class realizes a node with LSA concentration.



## Constructors


| | |
|---|---|
| [LsaNode](-lsa-node.html) | [jvm]<br>open fun [LsaNode](-lsa-node.html)(env: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html)>, out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>)<br>The environment (used for safe node id computation) |


## Functions


| Name | Summary |
|---|---|
| [addReaction](../-abstract-node/add-reaction.html) | [jvm]<br>fun [addReaction](../-abstract-node/add-reaction.html)(reactionToAdd: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist.model.implementations.actions/-abstract-action/index.html)>) |
| [cloneNode](../-abstract-node/clone-node.html) | [jvm]<br>open fun [cloneNode](../-abstract-node/clone-node.html)(currentTime: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html)): [AbstractNode](../-abstract-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.actions/-abstract-action/index.html)><br>abstract fun [cloneNode](../../it.unibo.alchemist.model.interfaces/-node/clone-node.html)(p: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html)): [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.actions/-abstract-action/index.html)> |
| [compareTo](../-abstract-node/compare-to.html) | [jvm]<br>fun [compareTo](../-abstract-node/compare-to.html)(other: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.actions/-abstract-action/index.html)>): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [contains](contains.html) | [jvm]<br>open fun [contains](contains.html)(m: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [equals](../-abstract-node/equals.html) | [jvm]<br>fun [equals](../-abstract-node/equals.html)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [forEach](../-abstract-node/for-each.html) | [jvm]<br>fun [forEach](../-abstract-node/for-each.html)(action: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |
| [getConcentration](get-concentration.html) | [jvm]<br>open fun [getConcentration](get-concentration.html)(m: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html)): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html)> |
| [getContents](get-contents.html) | [jvm]<br>open fun [getContents](get-contents.html)(): [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<[Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html), [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html)>> |
| [getId](../-homogeneous-physical-pedestrian2-d/index.html#2063123767%2FFunctions%2F-134779887) | [jvm]<br>fun [getId](../-homogeneous-physical-pedestrian2-d/index.html#2063123767%2FFunctions%2F-134779887)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getLsaSpace](get-lsa-space.html) | [jvm]<br>open fun [getLsaSpace](get-lsa-space.html)(): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html)><br>lsaMolecules in the node. |
| [getMoleculeCount](get-molecule-count.html) | [jvm]<br>open fun [getMoleculeCount](get-molecule-count.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getReactions](../-homogeneous-physical-pedestrian2-d/index.html#-301186114%2FFunctions%2F-134779887) | [jvm]<br>fun [getReactions](../-homogeneous-physical-pedestrian2-d/index.html#-301186114%2FFunctions%2F-134779887)(): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist.model.implementations.actions/-abstract-action/index.html)>> |
| [hashCode](../-abstract-node/hash-code.html) | [jvm]<br>fun [hashCode](../-abstract-node/hash-code.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [iterator](../-abstract-node/iterator.html) | [jvm]<br>fun [iterator](../-abstract-node/iterator.html)(): [Iterator](https://docs.oracle.com/javase/8/docs/api/java/util/Iterator.html)<[Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist.model.implementations.actions/-abstract-action/index.html)>><br>abstract fun [iterator](../../it.unibo.alchemist.loader.variables/-arbitrary-variable/index.html#-1606146105%2FFunctions%2F-134779887)(): [Iterator](https://docs.oracle.com/javase/8/docs/api/java/util/Iterator.html)<[T](../../it.unibo.alchemist.model.implementations.actions/-abstract-action/index.html)> |
| [removeConcentration](../-abstract-node/remove-concentration.html) | [jvm]<br>open fun [removeConcentration](../-abstract-node/remove-concentration.html)(moleculeToRemove: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html))<br>[jvm]<br>open fun [removeConcentration](remove-concentration.html)(matchedInstance: [ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Deletes an ILsaMolecule from the Node LsaSpace Warning: the method removes only the first matched ILsaMolecule. |
| [removeReaction](../-abstract-node/remove-reaction.html) | [jvm]<br>fun [removeReaction](../-abstract-node/remove-reaction.html)(reactionToRemove: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist.model.implementations.actions/-abstract-action/index.html)>) |
| [setConcentration](set-concentration.html) | [jvm]<br>open fun [setConcentration](set-concentration.html)(inst: [ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html))<br>Adds an instance of ILsaMolecule in the node's LsaSpace.<br>[jvm]<br>open fun [setConcentration](set-concentration.html)(mol: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html), c: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html)>) |
| [spliterator](../-abstract-node/spliterator.html) | [jvm]<br>fun [spliterator](../-abstract-node/spliterator.html)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist.model.implementations.actions/-abstract-action/index.html)>><br>open fun [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-677603448%2FFunctions%2F-134779887)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[T](../../it.unibo.alchemist.model.implementations.actions/-abstract-action/index.html)> |
| [toString](to-string.html) | [jvm]<br>open fun [toString](to-string.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |

