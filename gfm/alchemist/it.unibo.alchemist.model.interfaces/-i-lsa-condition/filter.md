//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces](../index.md)/[ILsaCondition](index.md)/[filter](filter.md)

# filter

[jvm]\
abstract fun [filter](filter.md)(matches: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<HashString, [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>>>, validNodes: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaNode](../-i-lsa-node/index.md)>, retrieved: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<[ILsaNode](../-i-lsa-node/index.md), [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../-i-lsa-molecule/index.md)>>>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)

When this method is called, the condition must filter the current matches and allowed nodes.

#### Return

true if the condition is valid, false otherwise

## Parameters

jvm

| | |
|---|---|
| matches | current matches. This map may be modified |
| validNodes | the list of the valid neighbors. This list may be modified |
| retrieved | the list of the the molecules removed for each node for each possible binding |
