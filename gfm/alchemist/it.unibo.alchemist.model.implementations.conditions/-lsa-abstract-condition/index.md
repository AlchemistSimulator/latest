//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.conditions](../index.md)/[LsaAbstractCondition](index.md)

# LsaAbstractCondition

[jvm]\
abstract class [LsaAbstractCondition](index.md) : [AbstractCondition](../-abstract-condition/index.md)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.md)>> , [ILsaCondition](../../it.unibo.alchemist.model.interfaces/-i-lsa-condition/index.md)

## Constructors

| | |
|---|---|
| [LsaAbstractCondition](-lsa-abstract-condition.md) | [jvm]<br>open fun [LsaAbstractCondition](-lsa-abstract-condition.md)(node: [ILsaNode](../../it.unibo.alchemist.model.interfaces/-i-lsa-node/index.md), m: [Set](https://docs.oracle.com/javase/8/docs/api/java/util/Set.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.md)>)<br>the node hosting this action |

## Functions

| Name | Summary |
|---|---|
| [cloneCondition](clone-condition.md) | [jvm]<br>abstract fun [cloneCondition](clone-condition.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.md)>>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.md)>>): [LsaAbstractCondition](index.md) |
| [filter](../../it.unibo.alchemist.model.interfaces/-i-lsa-condition/filter.md) | [jvm]<br>abstract fun [filter](../../it.unibo.alchemist.model.interfaces/-i-lsa-condition/filter.md)(matches: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<HashString, [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>>>, validNodes: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaNode](../../it.unibo.alchemist.model.interfaces/-i-lsa-node/index.md)>, retrieved: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<[ILsaNode](../../it.unibo.alchemist.model.interfaces/-i-lsa-node/index.md), [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.md)>>>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>When this method is called, the condition must filter the current matches and allowed nodes. |
| [getContext](../../it.unibo.alchemist.model.interfaces/-condition/get-context.md) | [jvm]<br>abstract fun [getContext](../../it.unibo.alchemist.model.interfaces/-condition/get-context.md)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.md) |
| [getInboundDependencies](../-abstract-condition/get-inbound-dependencies.md) | [jvm]<br>fun [getInboundDependencies](../-abstract-condition/get-inbound-dependencies.md)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.md)> |
| [getNode](get-node.md) | [jvm]<br>fun [getNode](get-node.md)(): [ILsaNode](../../it.unibo.alchemist.model.interfaces/-i-lsa-node/index.md) |
| [getPropensityContribution](../../it.unibo.alchemist.model.interfaces/-condition/get-propensity-contribution.md) | [jvm]<br>abstract fun [getPropensityContribution](../../it.unibo.alchemist.model.interfaces/-condition/get-propensity-contribution.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [isValid](../../it.unibo.alchemist.model.interfaces/-condition/is-valid.md) | [jvm]<br>abstract fun [isValid](../../it.unibo.alchemist.model.interfaces/-condition/is-valid.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [reactionReady](../../it.unibo.alchemist.model.interfaces/-condition/reaction-ready.md) | [jvm]<br>open fun [reactionReady](../../it.unibo.alchemist.model.interfaces/-condition/reaction-ready.md)() |
| [toString](to-string.md) | [jvm]<br>abstract fun [toString](to-string.md)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |

## Inheritors

| Name |
|---|
| [LsaStandardCondition](../-lsa-standard-condition/index.md) |
