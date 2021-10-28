//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces](../index.md)/[ILsaCondition](index.md)

# ILsaCondition

[jvm]\
interface [ILsaCondition](index.md) : [Condition](../-condition/index.md)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../-i-lsa-molecule/index.md)>>

## Functions

| Name | Summary |
|---|---|
| [cloneCondition](clone-condition.md) | [jvm]<br>abstract fun [cloneCondition](clone-condition.md)(node: [Node](../-node/index.md)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../-i-lsa-molecule/index.md)>>, reaction: [Reaction](../-reaction/index.md)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../-i-lsa-molecule/index.md)>>): [ILsaCondition](index.md) |
| [filter](filter.md) | [jvm]<br>abstract fun [filter](filter.md)(matches: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<HashString, [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>>>, validNodes: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaNode](../-i-lsa-node/index.md)>, retrieved: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<[ILsaNode](../-i-lsa-node/index.md), [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../-i-lsa-molecule/index.md)>>>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>When this method is called, the condition must filter the current matches and allowed nodes. |
| [getContext](../-condition/get-context.md) | [jvm]<br>abstract fun [getContext](../-condition/get-context.md)(): [Context](../-context/index.md) |
| [getInboundDependencies](../-condition/get-inbound-dependencies.md) | [jvm]<br>abstract fun [getInboundDependencies](../-condition/get-inbound-dependencies.md)(): ListSet<out [Dependency](../-dependency/index.md)> |
| [getNode](get-node.md) | [jvm]<br>abstract fun [getNode](get-node.md)(): [ILsaNode](../-i-lsa-node/index.md) |
| [getPropensityContribution](../-condition/get-propensity-contribution.md) | [jvm]<br>abstract fun [getPropensityContribution](../-condition/get-propensity-contribution.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [isValid](../-condition/is-valid.md) | [jvm]<br>abstract fun [isValid](../-condition/is-valid.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [reactionReady](../-condition/reaction-ready.md) | [jvm]<br>open fun [reactionReady](../-condition/reaction-ready.md)() |

## Inheritors

| Name |
|---|
| [LsaAbstractCondition](../../it.unibo.alchemist.model.implementations.conditions/-lsa-abstract-condition/index.md) |
