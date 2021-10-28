//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces](../index.md)/[ILsaAction](index.md)

# ILsaAction

[jvm]\
interface [ILsaAction](index.md) : [Action](../-action/index.md)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../-i-lsa-molecule/index.md)>>

## Functions

| Name | Summary |
|---|---|
| [cloneAction](clone-action.md) | [jvm]<br>abstract fun [cloneAction](clone-action.md)(node: [Node](../-node/index.md)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../-i-lsa-molecule/index.md)>>, reaction: [Reaction](../-reaction/index.md)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../-i-lsa-molecule/index.md)>>): [ILsaAction](index.md) |
| [execute](../-action/execute.md) | [jvm]<br>abstract fun [execute](../-action/execute.md)() |
| [getContext](../-action/get-context.md) | [jvm]<br>abstract fun [getContext](../-action/get-context.md)(): [Context](../-context/index.md) |
| [getOutboundDependencies](get-outbound-dependencies.md) | [jvm]<br>abstract fun [getOutboundDependencies](get-outbound-dependencies.md)(): ListSet<out [Dependency](../-dependency/index.md)> |
| [setExecutionContext](set-execution-context.md) | [jvm]<br>abstract fun [setExecutionContext](set-execution-context.md)(matches: [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<HashString, [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>>, nodes: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaNode](../-i-lsa-node/index.md)>)<br>Sets the context in which this action will execute. |

## Inheritors

| Name |
|---|
| [LsaAbstractAction](../../it.unibo.alchemist.model.implementations.actions/-lsa-abstract-action/index.md) |
| [SAPEREWalker](../../it.unibo.alchemist.model.implementations.actions/-s-a-p-e-r-e-walker/index.md) |
