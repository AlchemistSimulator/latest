//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.actions](../index.md)/[AbstractNeighborAction](index.md)

# AbstractNeighborAction

[jvm]\
abstract class [AbstractNeighborAction](index.md)<[T](index.md)> : [AbstractRandomizableAction](../-abstract-randomizable-action/index.md)<[T](../../it.unibo.alchemist.model.implementations.conditions/-abstract-condition/index.md)> 

Represents an action on a neighbor.

## Parameters

jvm

| | |
|---|---|
| <T> | the concentration type. |

## Functions

| Name | Summary |
|---|---|
| [cloneAction](clone-action.md) | [jvm]<br>abstract fun [cloneAction](clone-action.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.conditions/-abstract-condition/index.md)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](../../it.unibo.alchemist.model.implementations.conditions/-abstract-condition/index.md)>): [AbstractNeighborAction](index.md)<[T](../../it.unibo.alchemist.model.implementations.conditions/-abstract-condition/index.md)> |
| [execute](execute.md) | [jvm]<br>open fun [execute](execute.md)()<br>Execute the action on a random neighbor if the node has a neighborhood.<br>[jvm]<br>abstract fun [execute](execute.md)(targetNode: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.conditions/-abstract-condition/index.md)>)<br>Execute the action on the given target node. |
| [getContext](get-context.md) | [jvm]<br>fun [getContext](get-context.md)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.md) |
| [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.md) | [jvm]<br>fun [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.md)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.md)> |
| [toString](../-abstract-action/to-string.md) | [jvm]<br>open fun [toString](../-abstract-action/to-string.md)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |

## Inheritors

| Name |
|---|
| [AddJunctionInNeighbor](../-add-junction-in-neighbor/index.md) |
| [AddJunctionInCell](../-add-junction-in-cell/index.md) |
| [ChangeBiomolConcentrationInNeighbor](../-change-biomol-concentration-in-neighbor/index.md) |
| [RemoveJunctionInCell](../-remove-junction-in-cell/index.md) |
| [RemoveJunctionInNeighbor](../-remove-junction-in-neighbor/index.md) |
