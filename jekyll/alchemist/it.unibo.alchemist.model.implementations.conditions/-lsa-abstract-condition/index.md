---
title: LsaAbstractCondition
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.conditions](../index.html)/[LsaAbstractCondition](index.html)



# LsaAbstractCondition



[jvm]\
abstract class [LsaAbstractCondition](index.html) : [AbstractCondition](../-abstract-condition/index.html)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html)>> , [ILsaCondition](../../it.unibo.alchemist.model.interfaces/-i-lsa-condition/index.html)



## Constructors


| | |
|---|---|
| [LsaAbstractCondition](-lsa-abstract-condition.html) | [jvm]<br>open fun [LsaAbstractCondition](-lsa-abstract-condition.html)(node: [ILsaNode](../../it.unibo.alchemist.model.interfaces/-i-lsa-node/index.html), m: [Set](https://docs.oracle.com/javase/8/docs/api/java/util/Set.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html)>)<br>the node hosting this action |


## Functions


| Name | Summary |
|---|---|
| [cloneCondition](clone-condition.html) | [jvm]<br>abstract fun [cloneCondition](clone-condition.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html)>>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html)>>): [LsaAbstractCondition](index.html) |
| [filter](../../it.unibo.alchemist.model.interfaces/-i-lsa-condition/filter.html) | [jvm]<br>abstract fun [filter](../../it.unibo.alchemist.model.interfaces/-i-lsa-condition/filter.html)(matches: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<HashString, [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>>>, validNodes: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaNode](../../it.unibo.alchemist.model.interfaces/-i-lsa-node/index.html)>, retrieved: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<[ILsaNode](../../it.unibo.alchemist.model.interfaces/-i-lsa-node/index.html), [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html)>>>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>When this method is called, the condition must filter the current matches and allowed nodes. |
| [getContext](../../it.unibo.alchemist.model.interfaces/-condition/get-context.html) | [jvm]<br>abstract fun [getContext](../../it.unibo.alchemist.model.interfaces/-condition/get-context.html)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.html) |
| [getInboundDependencies](../-abstract-condition/get-inbound-dependencies.html) | [jvm]<br>fun [getInboundDependencies](../-abstract-condition/get-inbound-dependencies.html)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)> |
| [getNode](get-node.html) | [jvm]<br>fun [getNode](get-node.html)(): [ILsaNode](../../it.unibo.alchemist.model.interfaces/-i-lsa-node/index.html) |
| [getPropensityContribution](../../it.unibo.alchemist.model.interfaces/-condition/get-propensity-contribution.html) | [jvm]<br>abstract fun [getPropensityContribution](../../it.unibo.alchemist.model.interfaces/-condition/get-propensity-contribution.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [isValid](../../it.unibo.alchemist.model.interfaces/-condition/is-valid.html) | [jvm]<br>abstract fun [isValid](../../it.unibo.alchemist.model.interfaces/-condition/is-valid.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [reactionReady](../../it.unibo.alchemist.model.interfaces/-condition/reaction-ready.html) | [jvm]<br>open fun [reactionReady](../../it.unibo.alchemist.model.interfaces/-condition/reaction-ready.html)() |
| [toString](to-string.html) | [jvm]<br>abstract fun [toString](to-string.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |


## Inheritors


| Name |
|---|
| [LsaStandardCondition](../-lsa-standard-condition/index.html) |

