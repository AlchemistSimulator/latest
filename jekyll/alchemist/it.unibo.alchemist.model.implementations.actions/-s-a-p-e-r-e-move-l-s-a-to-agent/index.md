---
title: SAPEREMoveLSAToAgent
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.actions](../index.html)/[SAPEREMoveLSAToAgent](index.html)



# SAPEREMoveLSAToAgent



[jvm]\
class [SAPEREMoveLSAToAgent](index.html) : [SAPEREAgent](../-s-a-p-e-r-e-agent/index.html)

This agent matches a template, removes a single instance of it from the current node and moves the LSA to another node (specified at creation time). Please note that, since the destination could be anywhere in the system, this action has a GLOBAL [Context](../../it.unibo.alchemist.model.interfaces/-context/index.html), and thus may trigger a large number of updates, slowing down the whole simulation. Handle with care.



## Constructors


| | |
|---|---|
| [SAPEREMoveLSAToAgent](-s-a-p-e-r-e-move-l-s-a-to-agent.html) | [jvm]<br>open fun [SAPEREMoveLSAToAgent](-s-a-p-e-r-e-move-l-s-a-to-agent.html)(env: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, node: [ILsaNode](../../it.unibo.alchemist.model.interfaces/-i-lsa-node/index.html), destId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), template: [ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html))<br>This is the constructor that should be called from DSL. |
| [SAPEREMoveLSAToAgent](-s-a-p-e-r-e-move-l-s-a-to-agent.html) | [jvm]<br>open fun [SAPEREMoveLSAToAgent](-s-a-p-e-r-e-move-l-s-a-to-agent.html)(node: [ILsaNode](../../it.unibo.alchemist.model.interfaces/-i-lsa-node/index.html), dest: [ILsaNode](../../it.unibo.alchemist.model.interfaces/-i-lsa-node/index.html), template: [ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html))<br>the source node, where this action is programmed |


## Functions


| Name | Summary |
|---|---|
| [cloneAction](../-lsa-abstract-action/clone-action.html) | [jvm]<br>abstract fun [cloneAction](../-lsa-abstract-action/clone-action.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html)>>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html)>>): [LsaAbstractAction](../-lsa-abstract-action/index.html)<br>open fun [cloneAction](../-s-a-p-e-r-e-agent/clone-action.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html)>>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html)>>): [SAPEREAgent](../-s-a-p-e-r-e-agent/index.html)<br>abstract fun [cloneAction](../../it.unibo.alchemist.model.interfaces/-action/clone-action.html)(p: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../-abstract-action/index.html)>, p1: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../-abstract-action/index.html)>): [Action](../../it.unibo.alchemist.model.interfaces/-action/index.html)<[T](../-abstract-action/index.html)><br>abstract fun [cloneAction](../../it.unibo.alchemist.model.interfaces/-i-lsa-action/clone-action.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html)>>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html)>>): [ILsaAction](../../it.unibo.alchemist.model.interfaces/-i-lsa-action/index.html) |
| [execute](execute.html) | [jvm]<br>open fun [execute](execute.html)() |
| [getContext](get-context.html) | [jvm]<br>open fun [getContext](get-context.html)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.html) |
| [getNode](../-lsa-abstract-action/get-node.html) | [jvm]<br>fun [getNode](../-lsa-abstract-action/get-node.html)(): [ILsaNode](../../it.unibo.alchemist.model.interfaces/-i-lsa-node/index.html) |
| [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.html) | [jvm]<br>fun [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.html)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)><br>abstract fun [getOutboundDependencies](../../it.unibo.alchemist.model.interfaces/-i-lsa-action/get-outbound-dependencies.html)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)> |
| [setExecutionContext](../-lsa-abstract-action/set-execution-context.html) | [jvm]<br>open fun [setExecutionContext](../-lsa-abstract-action/set-execution-context.html)(m: [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<HashString, [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>>, n: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaNode](../../it.unibo.alchemist.model.interfaces/-i-lsa-node/index.html)>)<br>abstract fun [setExecutionContext](../../it.unibo.alchemist.model.interfaces/-i-lsa-action/set-execution-context.html)(matches: [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<HashString, [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>>, nodes: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaNode](../../it.unibo.alchemist.model.interfaces/-i-lsa-node/index.html)>)<br>Sets the context in which this action will execute. |
| [toString](../-abstract-action/to-string.html) | [jvm]<br>open fun [toString](../-abstract-action/to-string.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)<br>open fun [toString](../-s-a-p-e-r-e-agent/to-string.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |

