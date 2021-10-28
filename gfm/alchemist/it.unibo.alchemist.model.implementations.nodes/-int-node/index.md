//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.nodes](../index.md)/[IntNode](index.md)

# IntNode

[jvm]\
open class [IntNode](index.md)(**env**: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<*, *>) : [AbstractNode](../-abstract-node/index.md)<[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)> 

An integer node.

## Constructors

| | |
|---|---|
| [IntNode](-int-node.md) | [jvm]<br>fun [IntNode](-int-node.md)(env: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<*, *>) |

## Functions

| Name | Summary |
|---|---|
| [addReaction](index.md#-706714570%2FFunctions%2F-267951372) | [jvm]<br>override fun [addReaction](index.md#-706714570%2FFunctions%2F-267951372)(reactionToAdd: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)>) |
| [cloneNode](../-homogeneous-physical-pedestrian2-d/index.md#1410251741%2FFunctions%2F-267951372) | [jvm]<br>open override fun [cloneNode](../-homogeneous-physical-pedestrian2-d/index.md#1410251741%2FFunctions%2F-267951372)(currentTime: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md)): [AbstractNode](../-abstract-node/index.md)<[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)> |
| [compareTo](index.md#713875175%2FFunctions%2F-267951372) | [jvm]<br>operator override fun [compareTo](index.md#713875175%2FFunctions%2F-267951372)(@NotNull()other: @NotNull()[Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)>): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [contains](../-homogeneous-physical-pedestrian2-d/index.md#-1500024274%2FFunctions%2F-267951372) | [jvm]<br>open operator override fun [contains](../-homogeneous-physical-pedestrian2-d/index.md#-1500024274%2FFunctions%2F-267951372)(molecule: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [equals](../-homogeneous-physical-pedestrian2-d/index.md#1855273807%2FFunctions%2F-267951372) | [jvm]<br>operator override fun [equals](../-homogeneous-physical-pedestrian2-d/index.md#1855273807%2FFunctions%2F-267951372)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [forEach](index.md#907742238%2FFunctions%2F-267951372) | [jvm]<br>override fun [forEach](index.md#907742238%2FFunctions%2F-267951372)(action: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<in [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)>>) |
| [getConcentration](../-homogeneous-physical-pedestrian2-d/index.md#-989109866%2FFunctions%2F-267951372) | [jvm]<br>open override fun [getConcentration](../-homogeneous-physical-pedestrian2-d/index.md#-989109866%2FFunctions%2F-267951372)(molecule: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getContents](../-abstract-node/get-contents.md) | [jvm]<br>open override fun [getContents](../-abstract-node/get-contents.md)(): [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)<[Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md), [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)> |
| [getId](../-homogeneous-physical-pedestrian2-d/index.md#2063123767%2FFunctions%2F-267951372) | [jvm]<br>override fun [getId](../-homogeneous-physical-pedestrian2-d/index.md#2063123767%2FFunctions%2F-267951372)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getMoleculeCount](../-abstract-node/get-molecule-count.md) | [jvm]<br>open override fun [getMoleculeCount](../-abstract-node/get-molecule-count.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getReactions](../-homogeneous-physical-pedestrian2-d/index.md#-301186114%2FFunctions%2F-267951372) | [jvm]<br>override fun [getReactions](../-homogeneous-physical-pedestrian2-d/index.md#-301186114%2FFunctions%2F-267951372)(): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)<[Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)>> |
| [hashCode](../-abstract-node/hash-code.md) | [jvm]<br>override fun [hashCode](../-abstract-node/hash-code.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [iterator](../-abstract-node/iterator.md) | [jvm]<br>operator override fun [iterator](../-abstract-node/iterator.md)(): [MutableIterator](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-iterator/index.html)<[Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)>> |
| [removeConcentration](../-homogeneous-physical-pedestrian2-d/index.md#571173562%2FFunctions%2F-267951372) | [jvm]<br>open override fun [removeConcentration](../-homogeneous-physical-pedestrian2-d/index.md#571173562%2FFunctions%2F-267951372)(moleculeToRemove: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md)) |
| [removeReaction](index.md#-1623318147%2FFunctions%2F-267951372) | [jvm]<br>override fun [removeReaction](index.md#-1623318147%2FFunctions%2F-267951372)(reactionToRemove: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)>) |
| [setConcentration](index.md#-234430341%2FFunctions%2F-267951372) | [jvm]<br>open override fun [setConcentration](index.md#-234430341%2FFunctions%2F-267951372)(molecule: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md), concentration: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [spliterator](../-abstract-node/spliterator.md) | [jvm]<br>override fun [spliterator](../-abstract-node/spliterator.md)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)>> |
| [toString](../-abstract-node/to-string.md) | [jvm]<br>open override fun [toString](../-abstract-node/to-string.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
