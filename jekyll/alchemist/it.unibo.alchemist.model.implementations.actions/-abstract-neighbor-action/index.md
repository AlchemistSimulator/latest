---
title: AbstractNeighborAction
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.actions](../index.html)/[AbstractNeighborAction](index.html)



# AbstractNeighborAction



[jvm]\
abstract class [AbstractNeighborAction](index.html)<[T](index.html)> : [AbstractRandomizableAction](../-abstract-randomizable-action/index.html)<[T](../../it.unibo.alchemist.model.interfaces/-environment/index.html)> 

Represents an action on a neighbor.



## Parameters


jvm

| | |
|---|---|
| <T> | the concentration type. |



## Functions


| Name | Summary |
|---|---|
| [cloneAction](clone-action.html) | [jvm]<br>abstract fun [cloneAction](clone-action.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.interfaces/-environment/index.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist.model.interfaces/-environment/index.html)>): [AbstractNeighborAction](index.html)<[T](../../it.unibo.alchemist.model.interfaces/-environment/index.html)> |
| [execute](execute.html) | [jvm]<br>open fun [execute](execute.html)()<br>Execute the action on a random neighbor if the node has a neighborhood.<br>[jvm]<br>abstract fun [execute](execute.html)(targetNode: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.interfaces/-environment/index.html)>)<br>Execute the action on the given target node. |
| [getContext](get-context.html) | [jvm]<br>fun [getContext](get-context.html)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.html) |
| [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.html) | [jvm]<br>fun [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.html)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)> |
| [toString](../-abstract-action/to-string.html) | [jvm]<br>open fun [toString](../-abstract-action/to-string.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |


## Inheritors


| Name |
|---|
| [AddJunctionInNeighbor](../-add-junction-in-neighbor/index.html) |
| [AddJunctionInCell](../-add-junction-in-cell/index.html) |
| [ChangeBiomolConcentrationInNeighbor](../-change-biomol-concentration-in-neighbor/index.html) |
| [RemoveJunctionInCell](../-remove-junction-in-cell/index.html) |
| [RemoveJunctionInNeighbor](../-remove-junction-in-neighbor/index.html) |

