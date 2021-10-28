//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.actions](../index.md)/[LsaAscendingGradientDist](index.md)

# LsaAscendingGradientDist

[jvm]\
class [LsaAscendingGradientDist](index.md)<[P](index.md) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<[P](index.md)>?> : [SAPERENeighborAgent](../-s-a-p-e-r-e-neighbor-agent/index.md)<[P](index.md)>

## Parameters

jvm

| | |
|---|---|
| <P> | position type |

## Constructors

| | |
|---|---|
| [LsaAscendingGradientDist](-lsa-ascending-gradient-dist.md) | [jvm]<br>open fun [LsaAscendingGradientDist](-lsa-ascending-gradient-dist.md)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.md)>, [P](index.md)>, node: [ILsaNode](../../it.unibo.alchemist.model.interfaces/-i-lsa-node/index.md))<br>environment |

## Functions

| Name | Summary |
|---|---|
| [cloneAction](../-lsa-abstract-action/clone-action.md) | [jvm]<br>abstract fun [cloneAction](../-lsa-abstract-action/clone-action.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.md)>>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.md)>>): [LsaAbstractAction](../-lsa-abstract-action/index.md)<br>open fun [cloneAction](../-s-a-p-e-r-e-agent/clone-action.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.md)>>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.md)>>): [SAPEREAgent](../-s-a-p-e-r-e-agent/index.md)<br>abstract fun [cloneAction](../../it.unibo.alchemist.model.interfaces/-action/clone-action.md)(p: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.conditions/-abstract-condition/index.md)>, p1: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](../../it.unibo.alchemist.model.implementations.conditions/-abstract-condition/index.md)>): [Action](../../it.unibo.alchemist.model.interfaces/-action/index.md)<[T](../../it.unibo.alchemist.model.implementations.conditions/-abstract-condition/index.md)><br>abstract fun [cloneAction](../../it.unibo.alchemist.model.interfaces/-i-lsa-action/clone-action.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.md)>>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.md)>>): [ILsaAction](../../it.unibo.alchemist.model.interfaces/-i-lsa-action/index.md) |
| [execute](execute.md) | [jvm]<br>open fun [execute](execute.md)() |
| [getContext](../-s-a-p-e-r-e-neighbor-agent/get-context.md) | [jvm]<br>fun [getContext](../-s-a-p-e-r-e-neighbor-agent/get-context.md)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.md)<br>abstract fun [getContext](../../it.unibo.alchemist.model.interfaces/-action/get-context.md)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.md) |
| [getNode](../-lsa-abstract-action/get-node.md) | [jvm]<br>fun [getNode](../-lsa-abstract-action/get-node.md)(): [ILsaNode](../../it.unibo.alchemist.model.interfaces/-i-lsa-node/index.md) |
| [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.md) | [jvm]<br>fun [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.md)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.md)><br>abstract fun [getOutboundDependencies](../../it.unibo.alchemist.model.interfaces/-i-lsa-action/get-outbound-dependencies.md)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.md)> |
| [setExecutionContext](../-lsa-abstract-action/set-execution-context.md) | [jvm]<br>open fun [setExecutionContext](../-lsa-abstract-action/set-execution-context.md)(m: [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<HashString, [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>>, n: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaNode](../../it.unibo.alchemist.model.interfaces/-i-lsa-node/index.md)>)<br>abstract fun [setExecutionContext](../../it.unibo.alchemist.model.interfaces/-i-lsa-action/set-execution-context.md)(matches: [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<HashString, [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>>, nodes: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaNode](../../it.unibo.alchemist.model.interfaces/-i-lsa-node/index.md)>)<br>Sets the context in which this action will execute. |
| [toString](../-abstract-action/to-string.md) | [jvm]<br>open fun [toString](../-abstract-action/to-string.md)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)<br>open fun [toString](../-s-a-p-e-r-e-agent/to-string.md)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |