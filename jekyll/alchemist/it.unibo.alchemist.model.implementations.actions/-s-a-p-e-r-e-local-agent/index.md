---
title: SAPERELocalAgent
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.actions](../index.html)/[SAPERELocalAgent](index.html)



# SAPERELocalAgent



[jvm]\
abstract class [SAPERELocalAgent](index.html) : [SAPEREAgent](../-s-a-p-e-r-e-agent/index.html)

A SAPERE Agent that does not do actions on neighbors.



## Constructors


| | |
|---|---|
| [SAPERELocalAgent](-s-a-p-e-r-e-local-agent.html) | [jvm]<br>open fun [SAPERELocalAgent](-s-a-p-e-r-e-local-agent.html)(node: [ILsaNode](../../it.unibo.alchemist.model.interfaces/-i-lsa-node/index.html))<br>Creates a new SAPERE Local Agent stub. |
| [SAPERELocalAgent](-s-a-p-e-r-e-local-agent.html) | [jvm]<br>open fun [SAPERELocalAgent](-s-a-p-e-r-e-local-agent.html)(node: [ILsaNode](../../it.unibo.alchemist.model.interfaces/-i-lsa-node/index.html), m1: [ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html))<br>Creates a new SAPERE Agent stub. |
| [SAPERELocalAgent](-s-a-p-e-r-e-local-agent.html) | [jvm]<br>open fun [SAPERELocalAgent](-s-a-p-e-r-e-local-agent.html)(node: [ILsaNode](../../it.unibo.alchemist.model.interfaces/-i-lsa-node/index.html), m1: [ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html), m2: [ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html))<br>Creates a new SAPERE Agent stub. |
| [SAPERELocalAgent](-s-a-p-e-r-e-local-agent.html) | [jvm]<br>open fun [SAPERELocalAgent](-s-a-p-e-r-e-local-agent.html)(node: [ILsaNode](../../it.unibo.alchemist.model.interfaces/-i-lsa-node/index.html), m1: [ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html), m2: [ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html), m3: [ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html))<br>Creates a new SAPERE Agent stub. |


## Functions


| Name | Summary |
|---|---|
| [cloneAction](../-lsa-abstract-action/clone-action.html) | [jvm]<br>abstract fun [cloneAction](../-lsa-abstract-action/clone-action.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html)>>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html)>>): [LsaAbstractAction](../-lsa-abstract-action/index.html)<br>open fun [cloneAction](../-s-a-p-e-r-e-agent/clone-action.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html)>>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html)>>): [SAPEREAgent](../-s-a-p-e-r-e-agent/index.html)<br>abstract fun [cloneAction](../../it.unibo.alchemist.model.interfaces/-action/clone-action.html)(p: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../-abstract-action/index.html)>, p1: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../-abstract-action/index.html)>): [Action](../../it.unibo.alchemist.model.interfaces/-action/index.html)<[T](../-abstract-action/index.html)><br>abstract fun [cloneAction](../../it.unibo.alchemist.model.interfaces/-i-lsa-action/clone-action.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html)>>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html)>>): [ILsaAction](../../it.unibo.alchemist.model.interfaces/-i-lsa-action/index.html) |
| [execute](../../it.unibo.alchemist.model.interfaces/-action/execute.html) | [jvm]<br>abstract fun [execute](../../it.unibo.alchemist.model.interfaces/-action/execute.html)() |
| [getContext](get-context.html) | [jvm]<br>fun [getContext](get-context.html)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.html) |
| [getNode](../-lsa-abstract-action/get-node.html) | [jvm]<br>fun [getNode](../-lsa-abstract-action/get-node.html)(): [ILsaNode](../../it.unibo.alchemist.model.interfaces/-i-lsa-node/index.html) |
| [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.html) | [jvm]<br>fun [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.html)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)><br>abstract fun [getOutboundDependencies](../../it.unibo.alchemist.model.interfaces/-i-lsa-action/get-outbound-dependencies.html)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)> |
| [setExecutionContext](../-lsa-abstract-action/set-execution-context.html) | [jvm]<br>open fun [setExecutionContext](../-lsa-abstract-action/set-execution-context.html)(m: [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<HashString, [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>>, n: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaNode](../../it.unibo.alchemist.model.interfaces/-i-lsa-node/index.html)>)<br>abstract fun [setExecutionContext](../../it.unibo.alchemist.model.interfaces/-i-lsa-action/set-execution-context.html)(matches: [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<HashString, [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>>, nodes: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaNode](../../it.unibo.alchemist.model.interfaces/-i-lsa-node/index.html)>)<br>Sets the context in which this action will execute. |
| [toString](../-abstract-action/to-string.html) | [jvm]<br>open fun [toString](../-abstract-action/to-string.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)<br>open fun [toString](../-s-a-p-e-r-e-agent/to-string.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |


## Inheritors


| Name |
|---|
| [LsaCountNeighborsAction](../-lsa-count-neighbors-action/index.html) |
| [SAPEREMoveNodeAgent](../-s-a-p-e-r-e-move-node-agent/index.html) |
| [LsaChangeArgument](../-lsa-change-argument/index.html) |

