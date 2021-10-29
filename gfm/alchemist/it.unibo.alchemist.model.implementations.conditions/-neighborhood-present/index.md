//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.conditions](../index.md)/[NeighborhoodPresent](index.md)

# NeighborhoodPresent

[jvm]\
class [NeighborhoodPresent](index.md)<[T](index.md)> : [AbstractNeighborCondition](../-abstract-neighbor-condition/index.md)<[T](../-generic-molecule-present/index.md)> 

A condition is valid if the node has a neighborhood, formally if the node has at least one node connected by a linking rule.

## Parameters

jvm

| | |
|---|---|
| <T> | The concentration type. |

## Constructors

| | |
|---|---|
| [NeighborhoodPresent](-neighborhood-present.md) | [jvm]<br>open fun [NeighborhoodPresent](-neighborhood-present.md)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](../-generic-molecule-present/index.md), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../-generic-molecule-present/index.md)>)<br>Create the condition. |

## Functions

| Name | Summary |
|---|---|
| [cloneCondition](../-abstract-condition/clone-condition.md) | [jvm]<br>open fun [cloneCondition](../-abstract-condition/clone-condition.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../-generic-molecule-present/index.md)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](../-generic-molecule-present/index.md)>): [Condition](../../it.unibo.alchemist.model.interfaces/-condition/index.md)<[T](../-generic-molecule-present/index.md)><br>open fun [cloneCondition](clone-condition.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../-generic-molecule-present/index.md)>, r: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](../-generic-molecule-present/index.md)>): [NeighborhoodPresent](index.md)<[T](../-generic-molecule-present/index.md)> |
| [getContext](../-abstract-neighbor-condition/get-context.md) | [jvm]<br>fun [getContext](../-abstract-neighbor-condition/get-context.md)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.md)<br>abstract fun [getContext](../../it.unibo.alchemist.model.interfaces/-condition/get-context.md)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.md) |
| [getInboundDependencies](../-abstract-condition/get-inbound-dependencies.md) | [jvm]<br>fun [getInboundDependencies](../-abstract-condition/get-inbound-dependencies.md)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.md)> |
| [getNode](../-lsa-standard-condition/index.md#-1460695024%2FFunctions%2F-267951372) | [jvm]<br>open fun [getNode](../-lsa-standard-condition/index.md#-1460695024%2FFunctions%2F-267951372)(): [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../-generic-molecule-present/index.md)> |
| [getPropensityContribution](../-abstract-neighbor-condition/get-propensity-contribution.md) | [jvm]<br>open fun [getPropensityContribution](../-abstract-neighbor-condition/get-propensity-contribution.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Override if desired behavior differs.<br>[jvm]<br>abstract fun [getPropensityContribution](../../it.unibo.alchemist.model.interfaces/-condition/get-propensity-contribution.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getValidNeighbors](../-abstract-neighbor-condition/get-valid-neighbors.md) | [jvm]<br>fun [getValidNeighbors](../-abstract-neighbor-condition/get-valid-neighbors.md)(): [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<[Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../-generic-molecule-present/index.md)>, [Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)><br>Searches in the given neighborhood which nodes satisfy the condition, and returns a list of valid neighbors. |
| [isValid](is-valid.md) | [jvm]<br>open fun [isValid](is-valid.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [reactionReady](../../it.unibo.alchemist.model.interfaces/-condition/reaction-ready.md) | [jvm]<br>open fun [reactionReady](../../it.unibo.alchemist.model.interfaces/-condition/reaction-ready.md)() |
| [toString](to-string.md) | [jvm]<br>open fun [toString](to-string.md)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |
