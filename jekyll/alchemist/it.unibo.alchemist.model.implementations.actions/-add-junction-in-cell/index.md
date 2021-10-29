---
title: AddJunctionInCell
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.actions](../index.html)/[AddJunctionInCell](index.html)



# AddJunctionInCell



[jvm]\
class [AddJunctionInCell](index.html) : [AbstractNeighborAction](../-abstract-neighbor-action/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)> 

Represent the action of add a junction between the current node and a neighbor. This action only create the junction reference inside this node, the neighbor totally ignore that a junction has been created. This is a part of the junction creation process. See [AddJunctionInNeighbor](../-add-junction-in-neighbor/index.html) for the other part of the process



## Constructors


| | |
|---|---|
| [AddJunctionInCell](-add-junction-in-cell.html) | [jvm]<br>open fun [AddJunctionInCell](-add-junction-in-cell.html)(e: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, n: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>, j: [Junction](../../it.unibo.alchemist.model.implementations.molecules/-junction/index.html), rg: RandomGenerator)<br>the junction |


## Functions


| Name | Summary |
|---|---|
| [cloneAction](clone-action.html) | [jvm]<br>open fun [cloneAction](clone-action.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>): [AddJunctionInCell](index.html)<br>abstract fun [cloneAction](../../it.unibo.alchemist.model.interfaces/-action/clone-action.html)(p: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.reactions/-chemical-reaction/index.html)>, p1: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist.model.implementations.reactions/-chemical-reaction/index.html)>): [Action](../../it.unibo.alchemist.model.interfaces/-action/index.html)<[T](../../it.unibo.alchemist.model.implementations.reactions/-chemical-reaction/index.html)> |
| [execute](execute.html) | [jvm]<br>open fun [execute](execute.html)()<br>If no target node is given DO NOTHING.<br>[jvm]<br>abstract fun [execute](../../it.unibo.alchemist.model.interfaces/-action/execute.html)()<br>[jvm]<br>open fun [execute](execute.html)(targetNode: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>)<br>Create the junction that links the node where this action is executed and the target node. |
| [getContext](../-abstract-neighbor-action/get-context.html) | [jvm]<br>fun [getContext](../-abstract-neighbor-action/get-context.html)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.html)<br>abstract fun [getContext](../../it.unibo.alchemist.model.interfaces/-action/get-context.html)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.html) |
| [getNode](get-node.html) | [jvm]<br>open fun [getNode](get-node.html)(): [CellNode](../../it.unibo.alchemist.model.interfaces/-cell-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> |
| [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.html) | [jvm]<br>fun [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.html)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)> |
| [toString](to-string.html) | [jvm]<br>open fun [toString](to-string.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |

