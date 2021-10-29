---
title: EnvironmentNode
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces](../index.html)/[EnvironmentNode](index.html)



# EnvironmentNode



[jvm]\
interface [EnvironmentNode](index.html) : [Node](../-node/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>



## Functions


| Name | Summary |
|---|---|
| [addReaction](../-node/add-reaction.html) | [jvm]<br>abstract fun [addReaction](../-node/add-reaction.html)(p: [Reaction](../-reaction/index.html)<[T](../-environment/index.html)>) |
| [cloneNode](../-node/clone-node.html) | [jvm]<br>abstract fun [cloneNode](../-node/clone-node.html)(p: [Time](../-time/index.html)): [Node](../-node/index.html)<[T](../-environment/index.html)> |
| [compareTo](../-g-p-s-point/index.html#-1554281679%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [compareTo](../-g-p-s-point/index.html#-1554281679%2FFunctions%2F-134779887)(p: [T](../-environment/index.html)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [contains](../-node/contains.html) | [jvm]<br>abstract fun [contains](../-node/contains.html)(p: [Molecule](../-molecule/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-655675525%2FFunctions%2F-134779887) | [jvm]<br>open fun [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-655675525%2FFunctions%2F-134779887)(action: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |
| [getConcentration](../-node/get-concentration.html) | [jvm]<br>abstract fun [getConcentration](../-node/get-concentration.html)(p: [Molecule](../-molecule/index.html)): [T](../-environment/index.html) |
| [getContents](../-node/get-contents.html) | [jvm]<br>abstract fun [getContents](../-node/get-contents.html)(): [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<[Molecule](../-molecule/index.html), [T](../-environment/index.html)> |
| [getId](../-node/get-id.html) | [jvm]<br>abstract fun [getId](../-node/get-id.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getMoleculeCount](../-node/get-molecule-count.html) | [jvm]<br>abstract fun [getMoleculeCount](../-node/get-molecule-count.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getReactions](../-node/get-reactions.html) | [jvm]<br>abstract fun [getReactions](../-node/get-reactions.html)(): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[Reaction](../-reaction/index.html)<[T](../-environment/index.html)>> |
| [hashCode](../-node/hash-code.html) | [jvm]<br>abstract fun [hashCode](../-node/hash-code.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [iterator](../../it.unibo.alchemist.loader.variables/-arbitrary-variable/index.html#-1606146105%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [iterator](../../it.unibo.alchemist.loader.variables/-arbitrary-variable/index.html#-1606146105%2FFunctions%2F-134779887)(): [Iterator](https://docs.oracle.com/javase/8/docs/api/java/util/Iterator.html)<[T](../-environment/index.html)> |
| [removeConcentration](../-node/remove-concentration.html) | [jvm]<br>abstract fun [removeConcentration](../-node/remove-concentration.html)(p: [Molecule](../-molecule/index.html)) |
| [removeReaction](../-node/remove-reaction.html) | [jvm]<br>abstract fun [removeReaction](../-node/remove-reaction.html)(p: [Reaction](../-reaction/index.html)<[T](../-environment/index.html)>) |
| [setConcentration](../-node/set-concentration.html) | [jvm]<br>abstract fun [setConcentration](../-node/set-concentration.html)(p: [Molecule](../-molecule/index.html), p1: [T](../-environment/index.html)) |
| [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-677603448%2FFunctions%2F-134779887) | [jvm]<br>open fun [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-677603448%2FFunctions%2F-134779887)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[T](../-environment/index.html)> |


## Inheritors


| Name |
|---|
| [EnvironmentNodeImpl](../../it.unibo.alchemist.model.implementations.nodes/-environment-node-impl/index.html) |

