//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.nodes](../index.md)/[DoubleNode](index.md)

# DoubleNode

[jvm]\
open class [DoubleNode](index.md) : [AbstractNode](../-abstract-node/index.md)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>

## Constructors

| | |
|---|---|
| [DoubleNode](-double-node.md) | [jvm]<br>open fun [DoubleNode](-double-node.md)(env: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>)<br>Builds a new DoubleNode. |

## Functions

| Name | Summary |
|---|---|
| [addReaction](../-abstract-node/add-reaction.md) | [jvm]<br>fun [addReaction](../-abstract-node/add-reaction.md)(reactionToAdd: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](../../it.unibo.alchemist.model.implementations.conditions/-neighborhood-present/index.md)>) |
| [cloneNode](../-abstract-node/clone-node.md) | [jvm]<br>open fun [cloneNode](../-abstract-node/clone-node.md)(currentTime: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md)): [AbstractNode](../-abstract-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.conditions/-neighborhood-present/index.md)><br>abstract fun [cloneNode](../../it.unibo.alchemist.model.interfaces/-node/clone-node.md)(p: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md)): [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.conditions/-neighborhood-present/index.md)> |
| [compareTo](../-abstract-node/compare-to.md) | [jvm]<br>fun [compareTo](../-abstract-node/compare-to.md)(other: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.conditions/-neighborhood-present/index.md)>): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [contains](../-abstract-node/contains.md) | [jvm]<br>open fun [contains](../-abstract-node/contains.md)(molecule: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [equals](../-abstract-node/equals.md) | [jvm]<br>fun [equals](../-abstract-node/equals.md)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [forEach](../-abstract-node/for-each.md) | [jvm]<br>fun [forEach](../-abstract-node/for-each.md)(action: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |
| [getConcentration](../-abstract-node/get-concentration.md) | [jvm]<br>open fun [getConcentration](../-abstract-node/get-concentration.md)(molecule: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md)): [T](../../it.unibo.alchemist.model.implementations.conditions/-neighborhood-present/index.md) |
| [getContents](../-abstract-node/get-contents.md) | [jvm]<br>open fun [getContents](../-abstract-node/get-contents.md)(): [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<[Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md), [T](../../it.unibo.alchemist.model.implementations.conditions/-neighborhood-present/index.md)> |
| [getId](../-homogeneous-physical-pedestrian2-d/index.md#2063123767%2FFunctions%2F-267951372) | [jvm]<br>fun [getId](../-homogeneous-physical-pedestrian2-d/index.md#2063123767%2FFunctions%2F-267951372)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getMoleculeCount](../-abstract-node/get-molecule-count.md) | [jvm]<br>open fun [getMoleculeCount](../-abstract-node/get-molecule-count.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getReactions](../-homogeneous-physical-pedestrian2-d/index.md#-301186114%2FFunctions%2F-267951372) | [jvm]<br>fun [getReactions](../-homogeneous-physical-pedestrian2-d/index.md#-301186114%2FFunctions%2F-267951372)(): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](../../it.unibo.alchemist.model.implementations.conditions/-neighborhood-present/index.md)>> |
| [hashCode](../-abstract-node/hash-code.md) | [jvm]<br>fun [hashCode](../-abstract-node/hash-code.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [iterator](../-abstract-node/iterator.md) | [jvm]<br>fun [iterator](../-abstract-node/iterator.md)(): [Iterator](https://docs.oracle.com/javase/8/docs/api/java/util/Iterator.html)<[Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](../../it.unibo.alchemist.model.implementations.conditions/-neighborhood-present/index.md)>><br>abstract fun [iterator](../../it.unibo.alchemist.loader.variables/-arbitrary-variable/index.md#-1606146105%2FFunctions%2F-267951372)(): [Iterator](https://docs.oracle.com/javase/8/docs/api/java/util/Iterator.html)<[T](../../it.unibo.alchemist.model.implementations.conditions/-neighborhood-present/index.md)> |
| [removeConcentration](../-abstract-node/remove-concentration.md) | [jvm]<br>open fun [removeConcentration](../-abstract-node/remove-concentration.md)(moleculeToRemove: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md)) |
| [removeReaction](../-abstract-node/remove-reaction.md) | [jvm]<br>fun [removeReaction](../-abstract-node/remove-reaction.md)(reactionToRemove: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](../../it.unibo.alchemist.model.implementations.conditions/-neighborhood-present/index.md)>) |
| [setConcentration](../-abstract-node/set-concentration.md) | [jvm]<br>open fun [setConcentration](../-abstract-node/set-concentration.md)(molecule: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md), concentration: [T](../../it.unibo.alchemist.model.implementations.conditions/-neighborhood-present/index.md)) |
| [spliterator](../-abstract-node/spliterator.md) | [jvm]<br>fun [spliterator](../-abstract-node/spliterator.md)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](../../it.unibo.alchemist.model.implementations.conditions/-neighborhood-present/index.md)>><br>open fun [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-677603448%2FFunctions%2F-267951372)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[T](../../it.unibo.alchemist.model.implementations.conditions/-neighborhood-present/index.md)> |
| [toString](../-abstract-node/to-string.md) | [jvm]<br>open fun [toString](../-abstract-node/to-string.md)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |

## Inheritors

| Name |
|---|
| [CellNodeImpl](../-cell-node-impl/index.md) |
| [EnvironmentNodeImpl](../-environment-node-impl/index.md) |