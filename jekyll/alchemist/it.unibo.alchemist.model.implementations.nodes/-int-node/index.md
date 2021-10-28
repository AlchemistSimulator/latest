---
title: IntNode
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.nodes](../index.html)/[IntNode](index.html)



# IntNode



[jvm]\
open class [IntNode](index.html)(**env**: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<*, *>) : [AbstractNode](../-abstract-node/index.html)<[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)> 

An integer node.



## Constructors


| | |
|---|---|
| [IntNode](-int-node.html) | [jvm]<br>fun [IntNode](-int-node.html)(env: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<*, *>) |


## Functions


| Name | Summary |
|---|---|
| [addReaction](index.html#-706714570%2FFunctions%2F-134779887) | [jvm]<br>override fun [addReaction](index.html#-706714570%2FFunctions%2F-134779887)(reactionToAdd: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)>) |
| [cloneNode](../-homogeneous-physical-pedestrian2-d/index.html#1410251741%2FFunctions%2F-134779887) | [jvm]<br>open override fun [cloneNode](../-homogeneous-physical-pedestrian2-d/index.html#1410251741%2FFunctions%2F-134779887)(currentTime: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html)): [AbstractNode](../-abstract-node/index.html)<[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)> |
| [compareTo](index.html#713875175%2FFunctions%2F-134779887) | [jvm]<br>operator override fun [compareTo](index.html#713875175%2FFunctions%2F-134779887)(@NotNull()other: @NotNull()[Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)>): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [contains](../-homogeneous-physical-pedestrian2-d/index.html#-1500024274%2FFunctions%2F-134779887) | [jvm]<br>open operator override fun [contains](../-homogeneous-physical-pedestrian2-d/index.html#-1500024274%2FFunctions%2F-134779887)(molecule: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [equals](../-homogeneous-physical-pedestrian2-d/index.html#1855273807%2FFunctions%2F-134779887) | [jvm]<br>operator override fun [equals](../-homogeneous-physical-pedestrian2-d/index.html#1855273807%2FFunctions%2F-134779887)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [forEach](index.html#907742238%2FFunctions%2F-134779887) | [jvm]<br>override fun [forEach](index.html#907742238%2FFunctions%2F-134779887)(action: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<in [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)>>) |
| [getConcentration](../-homogeneous-physical-pedestrian2-d/index.html#-989109866%2FFunctions%2F-134779887) | [jvm]<br>open override fun [getConcentration](../-homogeneous-physical-pedestrian2-d/index.html#-989109866%2FFunctions%2F-134779887)(molecule: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getContents](../-abstract-node/get-contents.html) | [jvm]<br>open override fun [getContents](../-abstract-node/get-contents.html)(): [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)<[Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html), [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)> |
| [getId](../-homogeneous-physical-pedestrian2-d/index.html#2063123767%2FFunctions%2F-134779887) | [jvm]<br>override fun [getId](../-homogeneous-physical-pedestrian2-d/index.html#2063123767%2FFunctions%2F-134779887)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getMoleculeCount](../-abstract-node/get-molecule-count.html) | [jvm]<br>open override fun [getMoleculeCount](../-abstract-node/get-molecule-count.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getReactions](../-homogeneous-physical-pedestrian2-d/index.html#-301186114%2FFunctions%2F-134779887) | [jvm]<br>override fun [getReactions](../-homogeneous-physical-pedestrian2-d/index.html#-301186114%2FFunctions%2F-134779887)(): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)<[Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)>> |
| [hashCode](../-abstract-node/hash-code.html) | [jvm]<br>override fun [hashCode](../-abstract-node/hash-code.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [iterator](../-abstract-node/iterator.html) | [jvm]<br>operator override fun [iterator](../-abstract-node/iterator.html)(): [MutableIterator](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-iterator/index.html)<[Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)>> |
| [removeConcentration](../-homogeneous-physical-pedestrian2-d/index.html#571173562%2FFunctions%2F-134779887) | [jvm]<br>open override fun [removeConcentration](../-homogeneous-physical-pedestrian2-d/index.html#571173562%2FFunctions%2F-134779887)(moleculeToRemove: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html)) |
| [removeReaction](index.html#-1623318147%2FFunctions%2F-134779887) | [jvm]<br>override fun [removeReaction](index.html#-1623318147%2FFunctions%2F-134779887)(reactionToRemove: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)>) |
| [setConcentration](index.html#-234430341%2FFunctions%2F-134779887) | [jvm]<br>open override fun [setConcentration](index.html#-234430341%2FFunctions%2F-134779887)(molecule: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html), concentration: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [spliterator](../-abstract-node/spliterator.html) | [jvm]<br>override fun [spliterator](../-abstract-node/spliterator.html)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)>> |
| [toString](../-abstract-node/to-string.html) | [jvm]<br>open override fun [toString](../-abstract-node/to-string.html)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

