---
title: SAPEREAgent
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.actions](../index.html)/[SAPEREAgent](index.html)



# SAPEREAgent



[jvm]\
abstract class [SAPEREAgent](index.html) : [LsaAbstractAction](../-lsa-abstract-action/index.html)



## Constructors


| | |
|---|---|
| [SAPEREAgent](-s-a-p-e-r-e-agent.html) | [jvm]<br>open fun [SAPEREAgent](-s-a-p-e-r-e-agent.html)(node: [ILsaNode](../../it.unibo.alchemist.model.interfaces/-i-lsa-node/index.html))<br>Creates a new SAPERE Agent stub. |
| [SAPEREAgent](-s-a-p-e-r-e-agent.html) | [jvm]<br>open fun [SAPEREAgent](-s-a-p-e-r-e-agent.html)(node: [ILsaNode](../../it.unibo.alchemist.model.interfaces/-i-lsa-node/index.html), m1: [ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html))<br>Creates a new SAPERE Agent stub. |
| [SAPEREAgent](-s-a-p-e-r-e-agent.html) | [jvm]<br>open fun [SAPEREAgent](-s-a-p-e-r-e-agent.html)(node: [ILsaNode](../../it.unibo.alchemist.model.interfaces/-i-lsa-node/index.html), m1: [ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html), m2: [ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html))<br>Creates a new SAPERE Agent stub. |
| [SAPEREAgent](-s-a-p-e-r-e-agent.html) | [jvm]<br>open fun [SAPEREAgent](-s-a-p-e-r-e-agent.html)(node: [ILsaNode](../../it.unibo.alchemist.model.interfaces/-i-lsa-node/index.html), m1: [ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html), m2: [ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html), m3: [ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html))<br>Creates a new SAPERE Agent stub. |


## Functions


| Name | Summary |
|---|---|
| [cloneAction](clone-action.html) | [jvm]<br>open fun [cloneAction](clone-action.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html)>>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html)>>): [SAPEREAgent](index.html)<br>abstract fun [cloneAction](../../it.unibo.alchemist.model.interfaces/-action/clone-action.html)(p: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.conditions/-abstract-condition/index.html)>, p1: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist.model.implementations.conditions/-abstract-condition/index.html)>): [Action](../../it.unibo.alchemist.model.interfaces/-action/index.html)<[T](../../it.unibo.alchemist.model.implementations.conditions/-abstract-condition/index.html)><br>abstract fun [cloneAction](../../it.unibo.alchemist.model.interfaces/-i-lsa-action/clone-action.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html)>>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html)>>): [ILsaAction](../../it.unibo.alchemist.model.interfaces/-i-lsa-action/index.html) |
| [execute](../../it.unibo.alchemist.model.interfaces/-action/execute.html) | [jvm]<br>abstract fun [execute](../../it.unibo.alchemist.model.interfaces/-action/execute.html)() |
| [getContext](../../it.unibo.alchemist.model.interfaces/-action/get-context.html) | [jvm]<br>abstract fun [getContext](../../it.unibo.alchemist.model.interfaces/-action/get-context.html)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.html) |
| [getNode](../-lsa-abstract-action/get-node.html) | [jvm]<br>fun [getNode](../-lsa-abstract-action/get-node.html)(): [ILsaNode](../../it.unibo.alchemist.model.interfaces/-i-lsa-node/index.html) |
| [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.html) | [jvm]<br>fun [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.html)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)><br>abstract fun [getOutboundDependencies](../../it.unibo.alchemist.model.interfaces/-i-lsa-action/get-outbound-dependencies.html)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)> |
| [setExecutionContext](../-lsa-abstract-action/set-execution-context.html) | [jvm]<br>open fun [setExecutionContext](../-lsa-abstract-action/set-execution-context.html)(m: [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<HashString, [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>>, n: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaNode](../../it.unibo.alchemist.model.interfaces/-i-lsa-node/index.html)>)<br>abstract fun [setExecutionContext](../../it.unibo.alchemist.model.interfaces/-i-lsa-action/set-execution-context.html)(matches: [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<HashString, [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>>, nodes: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaNode](../../it.unibo.alchemist.model.interfaces/-i-lsa-node/index.html)>)<br>Sets the context in which this action will execute. |
| [toString](../-abstract-action/to-string.html) | [jvm]<br>open fun [toString](../-abstract-action/to-string.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)<br>open fun [toString](to-string.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |


## Inheritors


| Name |
|---|
| [SAPERELocalAgent](../-s-a-p-e-r-e-local-agent/index.html) |
| [SAPERENeighborAgent](../-s-a-p-e-r-e-neighbor-agent/index.html) |
| [SAPEREMoveLSAToAgent](../-s-a-p-e-r-e-move-l-s-a-to-agent/index.html) |

