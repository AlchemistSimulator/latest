//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.actions](../index.md)/[SAPERENeighborAgent](index.md)

# SAPERENeighborAgent

[jvm]\
abstract class [SAPERENeighborAgent](index.md)<[P](index.md) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<[P](../-lsa-ascending-gradient-dist/index.md)>?> : [SAPEREAgent](../-s-a-p-e-r-e-agent/index.md)

A SAPERE Agent that modifies something on neighboring nodes.

## Parameters

jvm

| | |
|---|---|
| <P> | position type |

## Constructors

| | |
|---|---|
| [SAPERENeighborAgent](-s-a-p-e-r-e-neighbor-agent.md) | [jvm]<br>open fun [SAPERENeighborAgent](-s-a-p-e-r-e-neighbor-agent.md)(env: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.md)>, [P](../-lsa-ascending-gradient-dist/index.md)>, node: [ILsaNode](../../it.unibo.alchemist.model.interfaces/-i-lsa-node/index.md), m1: [ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.md))<br>Creates a new SAPERE Neighbor Agent stub. |
| [SAPERENeighborAgent](-s-a-p-e-r-e-neighbor-agent.md) | [jvm]<br>open fun [SAPERENeighborAgent](-s-a-p-e-r-e-neighbor-agent.md)(env: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.md)>, [P](../-lsa-ascending-gradient-dist/index.md)>, node: [ILsaNode](../../it.unibo.alchemist.model.interfaces/-i-lsa-node/index.md), m1: [ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.md), m2: [ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.md))<br>Creates a new SAPERE Agent stub. |
| [SAPERENeighborAgent](-s-a-p-e-r-e-neighbor-agent.md) | [jvm]<br>open fun [SAPERENeighborAgent](-s-a-p-e-r-e-neighbor-agent.md)(env: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.md)>, [P](../-lsa-ascending-gradient-dist/index.md)>, node: [ILsaNode](../../it.unibo.alchemist.model.interfaces/-i-lsa-node/index.md), m1: [ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.md), m2: [ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.md), m3: [ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.md))<br>Creates a new SAPERE Agent stub. |

## Functions

| Name | Summary |
|---|---|
| [cloneAction](../-lsa-abstract-action/clone-action.md) | [jvm]<br>abstract fun [cloneAction](../-lsa-abstract-action/clone-action.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.md)>>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.md)>>): [LsaAbstractAction](../-lsa-abstract-action/index.md)<br>open fun [cloneAction](../-s-a-p-e-r-e-agent/clone-action.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.md)>>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.md)>>): [SAPEREAgent](../-s-a-p-e-r-e-agent/index.md)<br>abstract fun [cloneAction](../../it.unibo.alchemist.model.interfaces/-action/clone-action.md)(p: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.conditions/-abstract-condition/index.md)>, p1: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](../../it.unibo.alchemist.model.implementations.conditions/-abstract-condition/index.md)>): [Action](../../it.unibo.alchemist.model.interfaces/-action/index.md)<[T](../../it.unibo.alchemist.model.implementations.conditions/-abstract-condition/index.md)><br>abstract fun [cloneAction](../../it.unibo.alchemist.model.interfaces/-i-lsa-action/clone-action.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.md)>>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.md)>>): [ILsaAction](../../it.unibo.alchemist.model.interfaces/-i-lsa-action/index.md) |
| [execute](../../it.unibo.alchemist.model.interfaces/-action/execute.md) | [jvm]<br>abstract fun [execute](../../it.unibo.alchemist.model.interfaces/-action/execute.md)() |
| [getContext](get-context.md) | [jvm]<br>fun [getContext](get-context.md)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.md) |
| [getNode](../-lsa-abstract-action/get-node.md) | [jvm]<br>fun [getNode](../-lsa-abstract-action/get-node.md)(): [ILsaNode](../../it.unibo.alchemist.model.interfaces/-i-lsa-node/index.md) |
| [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.md) | [jvm]<br>fun [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.md)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.md)><br>abstract fun [getOutboundDependencies](../../it.unibo.alchemist.model.interfaces/-i-lsa-action/get-outbound-dependencies.md)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.md)> |
| [setExecutionContext](../-lsa-abstract-action/set-execution-context.md) | [jvm]<br>open fun [setExecutionContext](../-lsa-abstract-action/set-execution-context.md)(m: [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<HashString, [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>>, n: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaNode](../../it.unibo.alchemist.model.interfaces/-i-lsa-node/index.md)>)<br>abstract fun [setExecutionContext](../../it.unibo.alchemist.model.interfaces/-i-lsa-action/set-execution-context.md)(matches: [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<HashString, [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>>, nodes: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaNode](../../it.unibo.alchemist.model.interfaces/-i-lsa-node/index.md)>)<br>Sets the context in which this action will execute. |
| [toString](../-abstract-action/to-string.md) | [jvm]<br>open fun [toString](../-abstract-action/to-string.md)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)<br>open fun [toString](../-s-a-p-e-r-e-agent/to-string.md)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |

## Inheritors

| Name |
|---|
| [SAPEREChemotaxis](../-s-a-p-e-r-e-chemotaxis/index.md) |
| [LsaAscendingGradientDist](../-lsa-ascending-gradient-dist/index.md) |