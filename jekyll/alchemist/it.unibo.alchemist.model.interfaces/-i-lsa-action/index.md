---
title: ILsaAction
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces](../index.html)/[ILsaAction](index.html)



# ILsaAction



[jvm]\
interface [ILsaAction](index.html) : [Action](../-action/index.html)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../-i-lsa-molecule/index.html)>>



## Functions


| Name | Summary |
|---|---|
| [cloneAction](clone-action.html) | [jvm]<br>abstract fun [cloneAction](clone-action.html)(node: [Node](../-node/index.html)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../-i-lsa-molecule/index.html)>>, reaction: [Reaction](../-reaction/index.html)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../-i-lsa-molecule/index.html)>>): [ILsaAction](index.html) |
| [execute](../-action/execute.html) | [jvm]<br>abstract fun [execute](../-action/execute.html)() |
| [getContext](../-action/get-context.html) | [jvm]<br>abstract fun [getContext](../-action/get-context.html)(): [Context](../-context/index.html) |
| [getOutboundDependencies](get-outbound-dependencies.html) | [jvm]<br>abstract fun [getOutboundDependencies](get-outbound-dependencies.html)(): ListSet<out [Dependency](../-dependency/index.html)> |
| [setExecutionContext](set-execution-context.html) | [jvm]<br>abstract fun [setExecutionContext](set-execution-context.html)(matches: [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<HashString, [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>>, nodes: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaNode](../-i-lsa-node/index.html)>)<br>Sets the context in which this action will execute. |


## Inheritors


| Name |
|---|
| [LsaAbstractAction](../../it.unibo.alchemist.model.implementations.actions/-lsa-abstract-action/index.html) |
| [SAPEREWalker](../../it.unibo.alchemist.model.implementations.actions/-s-a-p-e-r-e-walker/index.html) |

