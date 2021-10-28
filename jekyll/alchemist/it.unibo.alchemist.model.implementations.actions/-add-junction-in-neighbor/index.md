---
title: AddJunctionInNeighbor
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.actions](../index.html)/[AddJunctionInNeighbor](index.html)



# AddJunctionInNeighbor



[jvm]\
class [AddJunctionInNeighbor](index.html)<[P](index.html) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<out [P](../../it.unibo.alchemist.model.implementations.layers/-biomol-gradient-layer/index.html)>?> : [AbstractNeighborAction](../-abstract-neighbor-action/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)> 

Represent the action of add a junction between a neighbor and the current node. This action only create the junction reference inside the neighbor, the current node totally ignore that a junction has been created. This is a part of the junction creation process. See [AddJunctionInCell](../-add-junction-in-cell/index.html) for the other part of the process



## Parameters


jvm

| | |
|---|---|
| <P> | Position type |



## Constructors


| | |
|---|---|
| [AddJunctionInNeighbor](-add-junction-in-neighbor.html) | [jvm]<br>open fun [AddJunctionInNeighbor](-add-junction-in-neighbor.html)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html), [P](../../it.unibo.alchemist.model.implementations.layers/-biomol-gradient-layer/index.html)>, node: [CellNode](../../it.unibo.alchemist.model.interfaces/-cell-node/index.html)<[P](../../it.unibo.alchemist.model.implementations.layers/-biomol-gradient-layer/index.html)>, junction: [Junction](../../it.unibo.alchemist.model.implementations.molecules/-junction/index.html), randomGenerator: RandomGenerator)<br>the junction |


## Functions


| Name | Summary |
|---|---|
| [cloneAction](clone-action.html) | [jvm]<br>open fun [cloneAction](clone-action.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>): [AddJunctionInNeighbor](index.html)<[P](../../it.unibo.alchemist.model.implementations.layers/-biomol-gradient-layer/index.html)><br>abstract fun [cloneAction](../../it.unibo.alchemist.model.interfaces/-action/clone-action.html)(p: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.conditions/-neighborhood-present/index.html)>, p1: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist.model.implementations.conditions/-neighborhood-present/index.html)>): [Action](../../it.unibo.alchemist.model.interfaces/-action/index.html)<[T](../../it.unibo.alchemist.model.implementations.conditions/-neighborhood-present/index.html)> |
| [execute](execute.html) | [jvm]<br>open fun [execute](execute.html)()<br>If no target node is given DO NOTHING.<br>[jvm]<br>abstract fun [execute](../../it.unibo.alchemist.model.interfaces/-action/execute.html)()<br>[jvm]<br>open fun [execute](execute.html)(targetNode: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>)<br>Create the junction that links the target node and the node when this action is executed. |
| [getContext](../-abstract-neighbor-action/get-context.html) | [jvm]<br>fun [getContext](../-abstract-neighbor-action/get-context.html)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.html)<br>abstract fun [getContext](../../it.unibo.alchemist.model.interfaces/-action/get-context.html)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.html) |
| [getNode](get-node.html) | [jvm]<br>open fun [getNode](get-node.html)(): [CellNode](../../it.unibo.alchemist.model.interfaces/-cell-node/index.html)<[P](../../it.unibo.alchemist.model.implementations.layers/-biomol-gradient-layer/index.html)> |
| [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.html) | [jvm]<br>fun [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.html)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)> |
| [toString](to-string.html) | [jvm]<br>open fun [toString](to-string.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |

