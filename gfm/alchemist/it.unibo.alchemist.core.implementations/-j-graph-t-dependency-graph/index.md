//[alchemist](../../../index.md)/[it.unibo.alchemist.core.implementations](../index.md)/[JGraphTDependencyGraph](index.md)

# JGraphTDependencyGraph

[jvm]\
class [JGraphTDependencyGraph](index.md)<[T](index.md)>(**environment**: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](index.md), *>) : [DependencyGraph](../../it.unibo.alchemist.core.interfaces/-dependency-graph/index.md)<[T](index.md)> 

This class offers an implementation of a dependency graph, namely a data structure which can address in an efficient way the problem of finding those reactions affected by the execution of another reaction. This class relies heavily on the ReactionHandler interface.

## Parameters

jvm

| | |
|---|---|
|  | <T> concentration type |

## Constructors

| | |
|---|---|
| [JGraphTDependencyGraph](-j-graph-t-dependency-graph.md) | [jvm]<br>fun <[T](index.md)> [JGraphTDependencyGraph](-j-graph-t-dependency-graph.md)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](index.md), *>)<br><T> concentration type |

## Functions

| Name | Summary |
|---|---|
| [addNeighbor](add-neighbor.md) | [jvm]<br>open override fun [addNeighbor](add-neighbor.md)(n1: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>, n2: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>) |
| [createDependencies](create-dependencies.md) | [jvm]<br>open override fun [createDependencies](create-dependencies.md)(newReaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](index.md)>) |
| [globalInputContextReactions](global-input-context-reactions.md) | [jvm]<br>open override fun [globalInputContextReactions](global-input-context-reactions.md)(): ListSet<[Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](index.md)>> |
| [outboundDependencies](outbound-dependencies.md) | [jvm]<br>open override fun [outboundDependencies](outbound-dependencies.md)(reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](index.md)>): ArrayListSet<[Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](index.md)>> |
| [removeDependencies](remove-dependencies.md) | [jvm]<br>open override fun [removeDependencies](remove-dependencies.md)(r: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](index.md)>) |
| [removeNeighbor](remove-neighbor.md) | [jvm]<br>open override fun [removeNeighbor](remove-neighbor.md)(n1: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>, n2: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>) |
| [toString](to-string.md) | [jvm]<br>open override fun [toString](to-string.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
