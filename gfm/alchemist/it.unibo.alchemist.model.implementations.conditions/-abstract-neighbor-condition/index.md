//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.conditions](../index.md)/[AbstractNeighborCondition](index.md)

# AbstractNeighborCondition

[jvm]\
abstract class [AbstractNeighborCondition](index.md)<[T](index.md)> : [AbstractCondition](../-abstract-condition/index.md)<[T](../../it.unibo.alchemist.model.implementations.nodes/-abstract-node/index.md)> 

Represents a condition on a neighbor. Formally this conditions is satisfied if at least one neighbor satisfy the condition.

## Parameters

jvm

| | |
|---|---|
| <T> | the concentration type. |

## Functions

| Name | Summary |
|---|---|
| [cloneCondition](clone-condition.md) | [jvm]<br>abstract fun [cloneCondition](clone-condition.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.nodes/-abstract-node/index.md)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](../../it.unibo.alchemist.model.implementations.nodes/-abstract-node/index.md)>): [AbstractNeighborCondition](index.md)<[T](../../it.unibo.alchemist.model.implementations.nodes/-abstract-node/index.md)> |
| [getContext](get-context.md) | [jvm]<br>fun [getContext](get-context.md)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.md) |
| [getInboundDependencies](../-abstract-condition/get-inbound-dependencies.md) | [jvm]<br>fun [getInboundDependencies](../-abstract-condition/get-inbound-dependencies.md)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.md)> |
| [getNode](../-lsa-standard-condition/index.md#-1460695024%2FFunctions%2F-267951372) | [jvm]<br>open fun [getNode](../-lsa-standard-condition/index.md#-1460695024%2FFunctions%2F-267951372)(): [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.nodes/-abstract-node/index.md)> |
| [getPropensityContribution](get-propensity-contribution.md) | [jvm]<br>open fun [getPropensityContribution](get-propensity-contribution.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Override if desired behavior differs. |
| [getValidNeighbors](get-valid-neighbors.md) | [jvm]<br>fun [getValidNeighbors](get-valid-neighbors.md)(): [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<[Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.nodes/-abstract-node/index.md)>, [Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)><br>Searches in the given neighborhood which nodes satisfy the condition, and returns a list of valid neighbors. |
| [isValid](../../it.unibo.alchemist.model.interfaces/-condition/is-valid.md) | [jvm]<br>abstract fun [isValid](../../it.unibo.alchemist.model.interfaces/-condition/is-valid.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [reactionReady](../../it.unibo.alchemist.model.interfaces/-condition/reaction-ready.md) | [jvm]<br>open fun [reactionReady](../../it.unibo.alchemist.model.interfaces/-condition/reaction-ready.md)() |
| [toString](../-abstract-condition/to-string.md) | [jvm]<br>open fun [toString](../-abstract-condition/to-string.md)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |

## Inheritors

| Name |
|---|
| [JunctionPresentInCell](../-junction-present-in-cell/index.md) |
| [BiomolPresentInNeighbor](../-biomol-present-in-neighbor/index.md) |
| [NeighborhoodPresent](../-neighborhood-present/index.md) |
