//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.conditions](../index.md)/[LsaStandardCondition](index.md)

# LsaStandardCondition

[jvm]\
open class [LsaStandardCondition](index.md) : [LsaAbstractCondition](../-lsa-abstract-condition/index.md)

simple LSA-condition (example: <grad,X,1>). Search an instance of a template in a node. The LSAMolecule matched, if exist, will not be deleted from the node Lsa-space . It can be deleted from the reaction, if necessary.

## Constructors

| | |
|---|---|
| [LsaStandardCondition](-lsa-standard-condition.md) | [jvm]<br>open fun [LsaStandardCondition](-lsa-standard-condition.md)(mol: [ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.md), n: [ILsaNode](../../it.unibo.alchemist.model.interfaces/-i-lsa-node/index.md))<br>Builds an LsaStandardCondition. |

## Functions

| Name | Summary |
|---|---|
| [cloneCondition](../-abstract-condition/clone-condition.md) | [jvm]<br>open fun [cloneCondition](../-abstract-condition/clone-condition.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../-abstract-condition/index.md)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](../-abstract-condition/index.md)>): [Condition](../../it.unibo.alchemist.model.interfaces/-condition/index.md)<[T](../-abstract-condition/index.md)><br>open fun [cloneCondition](clone-condition.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.md)>>, r: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.md)>>): [LsaStandardCondition](index.md)<br>abstract fun [cloneCondition](../../it.unibo.alchemist.model.interfaces/-i-lsa-condition/clone-condition.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.md)>>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.md)>>): [ILsaCondition](../../it.unibo.alchemist.model.interfaces/-i-lsa-condition/index.md) |
| [filter](filter.md) | [jvm]<br>open fun [filter](filter.md)(matchesList: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<HashString, [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>>>, validNodes: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaNode](../../it.unibo.alchemist.model.interfaces/-i-lsa-node/index.md)>, retrieved: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<[ILsaNode](../../it.unibo.alchemist.model.interfaces/-i-lsa-node/index.md), [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.md)>>>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>When this method is called, the condition must filter the current matches and allowed nodes. |
| [getContext](get-context.md) | [jvm]<br>open fun [getContext](get-context.md)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.md) |
| [getInboundDependencies](../-abstract-condition/get-inbound-dependencies.md) | [jvm]<br>fun [getInboundDependencies](../-abstract-condition/get-inbound-dependencies.md)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.md)> |
| [getNode](index.md#-1460695024%2FFunctions%2F-267951372) | [jvm]<br>open fun [getNode](index.md#-1460695024%2FFunctions%2F-267951372)(): [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../-abstract-condition/index.md)><br>fun [getNode](../-lsa-abstract-condition/get-node.md)(): [ILsaNode](../../it.unibo.alchemist.model.interfaces/-i-lsa-node/index.md) |
| [getPropensityContribution](get-propensity-contribution.md) | [jvm]<br>fun [getPropensityContribution](get-propensity-contribution.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [isValid](is-valid.md) | [jvm]<br>fun [isValid](is-valid.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [reactionReady](../../it.unibo.alchemist.model.interfaces/-condition/reaction-ready.md) | [jvm]<br>open fun [reactionReady](../../it.unibo.alchemist.model.interfaces/-condition/reaction-ready.md)() |
| [toString](../-abstract-condition/to-string.md) | [jvm]<br>open fun [toString](../-abstract-condition/to-string.md)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)<br>open fun [toString](to-string.md)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |

## Inheritors

| Name |
|---|
| [LsaNeighborhoodCondition](../-lsa-neighborhood-condition/index.md) |
