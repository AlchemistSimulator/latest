//[alchemist](../../../index.md)/[it.unibo.alchemist.core.interfaces](../index.md)/[DependencyGraph](index.md)

# DependencyGraph

[jvm]\
interface [DependencyGraph](index.md)<[T](index.md)>

This interface allows to separate the usage of a dependency graph from its implementation.

## Parameters

jvm

| | |
|---|---|
| <T> | The parametrization type for reactions |

## Functions

| Name | Summary |
|---|---|
| [addNeighbor](add-neighbor.md) | [jvm]<br>abstract fun [addNeighbor](add-neighbor.md)(n1: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.md)>, n2: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.md)>)<br>Given two nodes, the graph assumes they are now neighbors and calculates the neighborhood dependencies between them. |
| [createDependencies](create-dependencies.md) | [jvm]<br>abstract fun [createDependencies](create-dependencies.md)(rh: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.md)>)<br>This method creates the dependencies when a new reaction is added to the environment. |
| [globalInputContextReactions](global-input-context-reactions.md) | [jvm]<br>abstract fun [globalInputContextReactions](global-input-context-reactions.md)(): ListSet<[Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.md)>><br>the set of all reactions with a GLOBAL input context |
| [outboundDependencies](outbound-dependencies.md) | [jvm]<br>abstract fun [outboundDependencies](outbound-dependencies.md)(reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.md)>): ListSet<[Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.md)>><br>Returns the set of reactions that may be influenced by the provided reaction. |
| [removeDependencies](remove-dependencies.md) | [jvm]<br>abstract fun [removeDependencies](remove-dependencies.md)(rh: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.md)>)<br>This method removes all the dependencies (both in and out dependencies) for a given reaction handler. |
| [removeNeighbor](remove-neighbor.md) | [jvm]<br>abstract fun [removeNeighbor](remove-neighbor.md)(n1: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.md)>, n2: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.md)>)<br>Given two nodes, the engine assumes they are no longer neighbors and deletes the neighborhood dependencies between them. |

## Inheritors

| Name |
|---|
| [JGraphTDependencyGraph](../../it.unibo.alchemist.core.implementations/-j-graph-t-dependency-graph/index.md) |
