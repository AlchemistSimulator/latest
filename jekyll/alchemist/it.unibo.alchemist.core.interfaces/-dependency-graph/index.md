---
title: DependencyGraph
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.core.interfaces](../index.html)/[DependencyGraph](index.html)



# DependencyGraph



[jvm]\
interface [DependencyGraph](index.html)<[T](index.html)>

This interface allows to separate the usage of a dependency graph from its implementation.



## Parameters


jvm

| | |
|---|---|
| <T> | The parametrization type for reactions |



## Functions


| Name | Summary |
|---|---|
| [addNeighbor](add-neighbor.html) | [jvm]<br>abstract fun [addNeighbor](add-neighbor.html)(n1: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.interfaces/-node/index.html)>, n2: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.interfaces/-node/index.html)>)<br>Given two nodes, the graph assumes they are now neighbors and calculates the neighborhood dependencies between them. |
| [createDependencies](create-dependencies.html) | [jvm]<br>abstract fun [createDependencies](create-dependencies.html)(rh: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist.model.interfaces/-node/index.html)>)<br>This method creates the dependencies when a new reaction is added to the environment. |
| [globalInputContextReactions](global-input-context-reactions.html) | [jvm]<br>abstract fun [globalInputContextReactions](global-input-context-reactions.html)(): ListSet<[Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist.model.interfaces/-node/index.html)>><br>the set of all reactions with a GLOBAL input context |
| [outboundDependencies](outbound-dependencies.html) | [jvm]<br>abstract fun [outboundDependencies](outbound-dependencies.html)(reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist.model.interfaces/-node/index.html)>): ListSet<[Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist.model.interfaces/-node/index.html)>><br>Returns the set of reactions that may be influenced by the provided reaction. |
| [removeDependencies](remove-dependencies.html) | [jvm]<br>abstract fun [removeDependencies](remove-dependencies.html)(rh: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist.model.interfaces/-node/index.html)>)<br>This method removes all the dependencies (both in and out dependencies) for a given reaction handler. |
| [removeNeighbor](remove-neighbor.html) | [jvm]<br>abstract fun [removeNeighbor](remove-neighbor.html)(n1: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.interfaces/-node/index.html)>, n2: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.interfaces/-node/index.html)>)<br>Given two nodes, the engine assumes they are no longer neighbors and deletes the neighborhood dependencies between them. |


## Inheritors


| Name |
|---|
| [JGraphTDependencyGraph](../../it.unibo.alchemist.core.implementations/-j-graph-t-dependency-graph/index.html) |

