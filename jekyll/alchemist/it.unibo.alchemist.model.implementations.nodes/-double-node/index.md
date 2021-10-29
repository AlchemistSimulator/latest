---
title: DoubleNode
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.nodes](../index.html)/[DoubleNode](index.html)



# DoubleNode



[jvm]\
open class [DoubleNode](index.html) : [AbstractNode](../-abstract-node/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>



## Constructors


| | |
|---|---|
| [DoubleNode](-double-node.html) | [jvm]<br>open fun [DoubleNode](-double-node.html)(env: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>)<br>Builds a new DoubleNode. |


## Functions


| Name | Summary |
|---|---|
| [addReaction](../-abstract-node/add-reaction.html) | [jvm]<br>fun [addReaction](../-abstract-node/add-reaction.html)(reactionToAdd: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist.model.implementations.reactions/-chemical-reaction/index.html)>) |
| [cloneNode](../-abstract-node/clone-node.html) | [jvm]<br>open fun [cloneNode](../-abstract-node/clone-node.html)(currentTime: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html)): [AbstractNode](../-abstract-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.reactions/-chemical-reaction/index.html)><br>abstract fun [cloneNode](../../it.unibo.alchemist.model.interfaces/-node/clone-node.html)(p: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html)): [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.reactions/-chemical-reaction/index.html)> |
| [compareTo](../-abstract-node/compare-to.html) | [jvm]<br>fun [compareTo](../-abstract-node/compare-to.html)(other: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.reactions/-chemical-reaction/index.html)>): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [contains](../-abstract-node/contains.html) | [jvm]<br>open fun [contains](../-abstract-node/contains.html)(molecule: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [equals](../-abstract-node/equals.html) | [jvm]<br>fun [equals](../-abstract-node/equals.html)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [forEach](../-abstract-node/for-each.html) | [jvm]<br>fun [forEach](../-abstract-node/for-each.html)(action: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |
| [getConcentration](../-abstract-node/get-concentration.html) | [jvm]<br>open fun [getConcentration](../-abstract-node/get-concentration.html)(molecule: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html)): [T](../../it.unibo.alchemist.model.implementations.reactions/-chemical-reaction/index.html) |
| [getContents](../-abstract-node/get-contents.html) | [jvm]<br>open fun [getContents](../-abstract-node/get-contents.html)(): [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<[Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html), [T](../../it.unibo.alchemist.model.implementations.reactions/-chemical-reaction/index.html)> |
| [getId](../-homogeneous-physical-pedestrian2-d/index.html#2063123767%2FFunctions%2F-134779887) | [jvm]<br>fun [getId](../-homogeneous-physical-pedestrian2-d/index.html#2063123767%2FFunctions%2F-134779887)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getMoleculeCount](../-abstract-node/get-molecule-count.html) | [jvm]<br>open fun [getMoleculeCount](../-abstract-node/get-molecule-count.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getReactions](../-homogeneous-physical-pedestrian2-d/index.html#-301186114%2FFunctions%2F-134779887) | [jvm]<br>fun [getReactions](../-homogeneous-physical-pedestrian2-d/index.html#-301186114%2FFunctions%2F-134779887)(): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist.model.implementations.reactions/-chemical-reaction/index.html)>> |
| [hashCode](../-abstract-node/hash-code.html) | [jvm]<br>fun [hashCode](../-abstract-node/hash-code.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [iterator](../-abstract-node/iterator.html) | [jvm]<br>fun [iterator](../-abstract-node/iterator.html)(): [Iterator](https://docs.oracle.com/javase/8/docs/api/java/util/Iterator.html)<[Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist.model.implementations.reactions/-chemical-reaction/index.html)>><br>abstract fun [iterator](../../it.unibo.alchemist.loader.variables/-arbitrary-variable/index.html#-1606146105%2FFunctions%2F-134779887)(): [Iterator](https://docs.oracle.com/javase/8/docs/api/java/util/Iterator.html)<[T](../../it.unibo.alchemist.model.implementations.reactions/-chemical-reaction/index.html)> |
| [removeConcentration](../-abstract-node/remove-concentration.html) | [jvm]<br>open fun [removeConcentration](../-abstract-node/remove-concentration.html)(moleculeToRemove: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html)) |
| [removeReaction](../-abstract-node/remove-reaction.html) | [jvm]<br>fun [removeReaction](../-abstract-node/remove-reaction.html)(reactionToRemove: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist.model.implementations.reactions/-chemical-reaction/index.html)>) |
| [setConcentration](../-abstract-node/set-concentration.html) | [jvm]<br>open fun [setConcentration](../-abstract-node/set-concentration.html)(molecule: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html), concentration: [T](../../it.unibo.alchemist.model.implementations.reactions/-chemical-reaction/index.html)) |
| [spliterator](../-abstract-node/spliterator.html) | [jvm]<br>fun [spliterator](../-abstract-node/spliterator.html)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist.model.implementations.reactions/-chemical-reaction/index.html)>><br>open fun [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-677603448%2FFunctions%2F-134779887)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[T](../../it.unibo.alchemist.model.implementations.reactions/-chemical-reaction/index.html)> |
| [toString](../-abstract-node/to-string.html) | [jvm]<br>open fun [toString](../-abstract-node/to-string.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |


## Inheritors


| Name |
|---|
| [CellNodeImpl](../-cell-node-impl/index.html) |
| [EnvironmentNodeImpl](../-environment-node-impl/index.html) |

