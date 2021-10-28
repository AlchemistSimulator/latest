---
title: JGraphTDependencyGraph
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.core.implementations](../index.html)/[JGraphTDependencyGraph](index.html)



# JGraphTDependencyGraph



[jvm]\
class [JGraphTDependencyGraph](index.html)<[T](index.html)>(**environment**: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](index.html), *>) : [DependencyGraph](../../it.unibo.alchemist.core.interfaces/-dependency-graph/index.html)<[T](index.html)> 

This class offers an implementation of a dependency graph, namely a data structure which can address in an efficient way the problem of finding those reactions affected by the execution of another reaction. This class relies heavily on the ReactionHandler interface.



## Parameters


jvm

| | |
|---|---|
|  | <T> concentration type |



## Constructors


| | |
|---|---|
| [JGraphTDependencyGraph](-j-graph-t-dependency-graph.html) | [jvm]<br>fun <[T](index.html)> [JGraphTDependencyGraph](-j-graph-t-dependency-graph.html)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](index.html), *>)<br><T> concentration type |


## Functions


| Name | Summary |
|---|---|
| [addNeighbor](add-neighbor.html) | [jvm]<br>open override fun [addNeighbor](add-neighbor.html)(n1: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](index.html)>, n2: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](index.html)>) |
| [createDependencies](create-dependencies.html) | [jvm]<br>open override fun [createDependencies](create-dependencies.html)(newReaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](index.html)>) |
| [globalInputContextReactions](global-input-context-reactions.html) | [jvm]<br>open override fun [globalInputContextReactions](global-input-context-reactions.html)(): ListSet<[Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](index.html)>> |
| [outboundDependencies](outbound-dependencies.html) | [jvm]<br>open override fun [outboundDependencies](outbound-dependencies.html)(reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](index.html)>): ArrayListSet<[Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](index.html)>> |
| [removeDependencies](remove-dependencies.html) | [jvm]<br>open override fun [removeDependencies](remove-dependencies.html)(r: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](index.html)>) |
| [removeNeighbor](remove-neighbor.html) | [jvm]<br>open override fun [removeNeighbor](remove-neighbor.html)(n1: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](index.html)>, n2: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](index.html)>) |
| [toString](to-string.html) | [jvm]<br>open override fun [toString](to-string.html)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

