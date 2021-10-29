//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces](../index.md)/[EnvironmentNode](index.md)

# EnvironmentNode

[jvm]\
interface [EnvironmentNode](index.md) : [Node](../-node/index.md)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>

## Functions

| Name | Summary |
|---|---|
| [addReaction](../-node/add-reaction.md) | [jvm]<br>abstract fun [addReaction](../-node/add-reaction.md)(p: [Reaction](../-reaction/index.md)<[T](../../it.unibo.alchemist.model.implementations.conditions/-abstract-condition/index.md)>) |
| [cloneNode](../-node/clone-node.md) | [jvm]<br>abstract fun [cloneNode](../-node/clone-node.md)(p: [Time](../-time/index.md)): [Node](../-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.conditions/-abstract-condition/index.md)> |
| [compareTo](../-g-p-s-point/index.md#-1554281679%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [compareTo](../-g-p-s-point/index.md#-1554281679%2FFunctions%2F-267951372)(p: [T](../../it.unibo.alchemist.model.implementations.conditions/-abstract-condition/index.md)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [contains](../-node/contains.md) | [jvm]<br>abstract fun [contains](../-node/contains.md)(p: [Molecule](../-molecule/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-655675525%2FFunctions%2F-267951372) | [jvm]<br>open fun [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-655675525%2FFunctions%2F-267951372)(action: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |
| [getConcentration](../-node/get-concentration.md) | [jvm]<br>abstract fun [getConcentration](../-node/get-concentration.md)(p: [Molecule](../-molecule/index.md)): [T](../../it.unibo.alchemist.model.implementations.conditions/-abstract-condition/index.md) |
| [getContents](../-node/get-contents.md) | [jvm]<br>abstract fun [getContents](../-node/get-contents.md)(): [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<[Molecule](../-molecule/index.md), [T](../../it.unibo.alchemist.model.implementations.conditions/-abstract-condition/index.md)> |
| [getId](../-node/get-id.md) | [jvm]<br>abstract fun [getId](../-node/get-id.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getMoleculeCount](../-node/get-molecule-count.md) | [jvm]<br>abstract fun [getMoleculeCount](../-node/get-molecule-count.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getReactions](../-node/get-reactions.md) | [jvm]<br>abstract fun [getReactions](../-node/get-reactions.md)(): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[Reaction](../-reaction/index.md)<[T](../../it.unibo.alchemist.model.implementations.conditions/-abstract-condition/index.md)>> |
| [hashCode](../-node/hash-code.md) | [jvm]<br>abstract fun [hashCode](../-node/hash-code.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [iterator](../../it.unibo.alchemist.loader.variables/-arbitrary-variable/index.md#-1606146105%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [iterator](../../it.unibo.alchemist.loader.variables/-arbitrary-variable/index.md#-1606146105%2FFunctions%2F-267951372)(): [Iterator](https://docs.oracle.com/javase/8/docs/api/java/util/Iterator.html)<[T](../../it.unibo.alchemist.model.implementations.conditions/-abstract-condition/index.md)> |
| [removeConcentration](../-node/remove-concentration.md) | [jvm]<br>abstract fun [removeConcentration](../-node/remove-concentration.md)(p: [Molecule](../-molecule/index.md)) |
| [removeReaction](../-node/remove-reaction.md) | [jvm]<br>abstract fun [removeReaction](../-node/remove-reaction.md)(p: [Reaction](../-reaction/index.md)<[T](../../it.unibo.alchemist.model.implementations.conditions/-abstract-condition/index.md)>) |
| [setConcentration](../-node/set-concentration.md) | [jvm]<br>abstract fun [setConcentration](../-node/set-concentration.md)(p: [Molecule](../-molecule/index.md), p1: [T](../../it.unibo.alchemist.model.implementations.conditions/-abstract-condition/index.md)) |
| [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-677603448%2FFunctions%2F-267951372) | [jvm]<br>open fun [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-677603448%2FFunctions%2F-267951372)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[T](../../it.unibo.alchemist.model.implementations.conditions/-abstract-condition/index.md)> |

## Inheritors

| Name |
|---|
| [EnvironmentNodeImpl](../../it.unibo.alchemist.model.implementations.nodes/-environment-node-impl/index.md) |
