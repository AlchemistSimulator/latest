---
title: ILsaCondition
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces](../index.html)/[ILsaCondition](index.html)



# ILsaCondition



[jvm]\
interface [ILsaCondition](index.html) : [Condition](../-condition/index.html)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../-i-lsa-molecule/index.html)>>



## Functions


| Name | Summary |
|---|---|
| [cloneCondition](clone-condition.html) | [jvm]<br>abstract fun [cloneCondition](clone-condition.html)(node: [Node](../-node/index.html)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../-i-lsa-molecule/index.html)>>, reaction: [Reaction](../-reaction/index.html)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../-i-lsa-molecule/index.html)>>): [ILsaCondition](index.html) |
| [filter](filter.html) | [jvm]<br>abstract fun [filter](filter.html)(matches: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<HashString, [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>>>, validNodes: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaNode](../-i-lsa-node/index.html)>, retrieved: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<[ILsaNode](../-i-lsa-node/index.html), [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../-i-lsa-molecule/index.html)>>>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>When this method is called, the condition must filter the current matches and allowed nodes. |
| [getContext](../-condition/get-context.html) | [jvm]<br>abstract fun [getContext](../-condition/get-context.html)(): [Context](../-context/index.html) |
| [getInboundDependencies](../-condition/get-inbound-dependencies.html) | [jvm]<br>abstract fun [getInboundDependencies](../-condition/get-inbound-dependencies.html)(): ListSet<out [Dependency](../-dependency/index.html)> |
| [getNode](get-node.html) | [jvm]<br>abstract fun [getNode](get-node.html)(): [ILsaNode](../-i-lsa-node/index.html) |
| [getPropensityContribution](../-condition/get-propensity-contribution.html) | [jvm]<br>abstract fun [getPropensityContribution](../-condition/get-propensity-contribution.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [isValid](../-condition/is-valid.html) | [jvm]<br>abstract fun [isValid](../-condition/is-valid.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [reactionReady](../-condition/reaction-ready.html) | [jvm]<br>open fun [reactionReady](../-condition/reaction-ready.html)() |


## Inheritors


| Name |
|---|
| [LsaAbstractCondition](../../it.unibo.alchemist.model.implementations.conditions/-lsa-abstract-condition/index.html) |

