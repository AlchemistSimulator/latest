//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.actions](../index.md)/[RemoveJunctionInNeighbor](index.md)

# RemoveJunctionInNeighbor

[jvm]\
class [RemoveJunctionInNeighbor](index.md) : [AbstractNeighborAction](../-abstract-neighbor-action/index.md)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)> 

Represent the action of removing a junction between a neighbor and the current node. This action only remove the junction reference inside the neighbor node, the current one totally ignore that a junction has been removed. This is a part of the junction removal process. See [RemoveJunctionInCell](../-remove-junction-in-cell/index.md) for the other part of the process.

## Constructors

| | |
|---|---|
| [RemoveJunctionInNeighbor](-remove-junction-in-neighbor.md) | [jvm]<br>open fun [RemoveJunctionInNeighbor](-remove-junction-in-neighbor.md)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>, junction: [Junction](../../it.unibo.alchemist.model.implementations.molecules/-junction/index.md), randomGenerator: RandomGenerator)<br>junction to remove |

## Functions

| Name | Summary |
|---|---|
| [cloneAction](clone-action.md) | [jvm]<br>open fun [cloneAction](clone-action.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>): [RemoveJunctionInNeighbor](index.md)<br>abstract fun [cloneAction](../../it.unibo.alchemist.model.interfaces/-action/clone-action.md)(p: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.conditions/-generic-molecule-present/index.md)>, p1: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](../../it.unibo.alchemist.model.implementations.conditions/-generic-molecule-present/index.md)>): [Action](../../it.unibo.alchemist.model.interfaces/-action/index.md)<[T](../../it.unibo.alchemist.model.implementations.conditions/-generic-molecule-present/index.md)> |
| [execute](execute.md) | [jvm]<br>open fun [execute](execute.md)()<br>If no target node is given DO NOTHING.<br>[jvm]<br>abstract fun [execute](../../it.unibo.alchemist.model.interfaces/-action/execute.md)()<br>[jvm]<br>open fun [execute](execute.md)(targetNode: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>)<br>Execute the action on the given target node. |
| [getContext](../-abstract-neighbor-action/get-context.md) | [jvm]<br>fun [getContext](../-abstract-neighbor-action/get-context.md)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.md)<br>abstract fun [getContext](../../it.unibo.alchemist.model.interfaces/-action/get-context.md)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.md) |
| [getNode](get-node.md) | [jvm]<br>open fun [getNode](get-node.md)(): [CellNode](../../it.unibo.alchemist.model.interfaces/-cell-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> |
| [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.md) | [jvm]<br>fun [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.md)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.md)> |
| [toString](to-string.md) | [jvm]<br>open fun [toString](to-string.md)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |
