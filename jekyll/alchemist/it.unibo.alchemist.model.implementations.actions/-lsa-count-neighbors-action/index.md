---
title: LsaCountNeighborsAction
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.actions](../index.html)/[LsaCountNeighborsAction](index.html)



# LsaCountNeighborsAction



[jvm]\
class [LsaCountNeighborsAction](index.html) : [SAPERELocalAgent](../-s-a-p-e-r-e-local-agent/index.html)



## Constructors


| | |
|---|---|
| [LsaCountNeighborsAction](-lsa-count-neighbors-action.html) | [jvm]<br>open fun [LsaCountNeighborsAction](-lsa-count-neighbors-action.html)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html)>, out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, node: [ILsaNode](../../it.unibo.alchemist.model.interfaces/-i-lsa-node/index.html), molToCount: [ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html), countVar: HashString, rand: RandomGenerator)<br>Builds a new action that counts neighbors which contain in their lsaSpace an lsaMolecule matching mol. |
| [LsaCountNeighborsAction](-lsa-count-neighbors-action.html) | [jvm]<br>open fun [LsaCountNeighborsAction](-lsa-count-neighbors-action.html)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html)>, out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, node: [ILsaNode](../../it.unibo.alchemist.model.interfaces/-i-lsa-node/index.html), molToCount: [ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html), countVar: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), rand: RandomGenerator)<br>Builds a new action that counts neighbors which contain in their lsaSpace an lsaMolecule matching mol. |


## Functions


| Name | Summary |
|---|---|
| [cloneAction](../-lsa-abstract-action/clone-action.html) | [jvm]<br>abstract fun [cloneAction](../-lsa-abstract-action/clone-action.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html)>>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html)>>): [LsaAbstractAction](../-lsa-abstract-action/index.html)<br>open fun [cloneAction](clone-action.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html)>>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html)>>): [LsaCountNeighborsAction](index.html)<br>abstract fun [cloneAction](../../it.unibo.alchemist.model.interfaces/-action/clone-action.html)(p: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.conditions/-abstract-condition/index.html)>, p1: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist.model.implementations.conditions/-abstract-condition/index.html)>): [Action](../../it.unibo.alchemist.model.interfaces/-action/index.html)<[T](../../it.unibo.alchemist.model.implementations.conditions/-abstract-condition/index.html)><br>abstract fun [cloneAction](../../it.unibo.alchemist.model.interfaces/-i-lsa-action/clone-action.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html)>>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html)>>): [ILsaAction](../../it.unibo.alchemist.model.interfaces/-i-lsa-action/index.html) |
| [execute](execute.html) | [jvm]<br>open fun [execute](execute.html)() |
| [getContext](../-s-a-p-e-r-e-local-agent/get-context.html) | [jvm]<br>fun [getContext](../-s-a-p-e-r-e-local-agent/get-context.html)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.html)<br>abstract fun [getContext](../../it.unibo.alchemist.model.interfaces/-action/get-context.html)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.html) |
| [getNode](../-lsa-abstract-action/get-node.html) | [jvm]<br>fun [getNode](../-lsa-abstract-action/get-node.html)(): [ILsaNode](../../it.unibo.alchemist.model.interfaces/-i-lsa-node/index.html) |
| [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.html) | [jvm]<br>fun [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.html)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)><br>abstract fun [getOutboundDependencies](../../it.unibo.alchemist.model.interfaces/-i-lsa-action/get-outbound-dependencies.html)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)> |
| [setExecutionContext](../-lsa-abstract-action/set-execution-context.html) | [jvm]<br>open fun [setExecutionContext](../-lsa-abstract-action/set-execution-context.html)(m: [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<HashString, [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>>, n: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaNode](../../it.unibo.alchemist.model.interfaces/-i-lsa-node/index.html)>)<br>abstract fun [setExecutionContext](../../it.unibo.alchemist.model.interfaces/-i-lsa-action/set-execution-context.html)(matches: [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<HashString, [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>>, nodes: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaNode](../../it.unibo.alchemist.model.interfaces/-i-lsa-node/index.html)>)<br>Sets the context in which this action will execute. |
| [toString](../-abstract-action/to-string.html) | [jvm]<br>open fun [toString](../-abstract-action/to-string.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)<br>open fun [toString](to-string.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |

