---
title: AbstractNeighborCondition
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.conditions](../index.html)/[AbstractNeighborCondition](index.html)



# AbstractNeighborCondition



[jvm]\
abstract class [AbstractNeighborCondition](index.html)<[T](index.html)> : [AbstractCondition](../-abstract-condition/index.html)<[T](../../it.unibo.alchemist.model.interfaces/-environment/index.html)> 

Represents a condition on a neighbor. Formally this conditions is satisfied if at least one neighbor satisfy the condition.



## Parameters


jvm

| | |
|---|---|
| <T> | the concentration type. |



## Functions


| Name | Summary |
|---|---|
| [cloneCondition](clone-condition.html) | [jvm]<br>abstract fun [cloneCondition](clone-condition.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.interfaces/-environment/index.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist.model.interfaces/-environment/index.html)>): [AbstractNeighborCondition](index.html)<[T](../../it.unibo.alchemist.model.interfaces/-environment/index.html)> |
| [getContext](get-context.html) | [jvm]<br>fun [getContext](get-context.html)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.html) |
| [getInboundDependencies](../-abstract-condition/get-inbound-dependencies.html) | [jvm]<br>fun [getInboundDependencies](../-abstract-condition/get-inbound-dependencies.html)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)> |
| [getNode](../-lsa-standard-condition/index.html#-1460695024%2FFunctions%2F-134779887) | [jvm]<br>open fun [getNode](../-lsa-standard-condition/index.html#-1460695024%2FFunctions%2F-134779887)(): [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.interfaces/-environment/index.html)> |
| [getPropensityContribution](get-propensity-contribution.html) | [jvm]<br>open fun [getPropensityContribution](get-propensity-contribution.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Override if desired behavior differs. |
| [getValidNeighbors](get-valid-neighbors.html) | [jvm]<br>fun [getValidNeighbors](get-valid-neighbors.html)(): [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<[Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.interfaces/-environment/index.html)>, [Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)><br>Searches in the given neighborhood which nodes satisfy the condition, and returns a list of valid neighbors. |
| [isValid](../../it.unibo.alchemist.model.interfaces/-condition/is-valid.html) | [jvm]<br>abstract fun [isValid](../../it.unibo.alchemist.model.interfaces/-condition/is-valid.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [reactionReady](../../it.unibo.alchemist.model.interfaces/-condition/reaction-ready.html) | [jvm]<br>open fun [reactionReady](../../it.unibo.alchemist.model.interfaces/-condition/reaction-ready.html)() |
| [toString](../-abstract-condition/to-string.html) | [jvm]<br>open fun [toString](../-abstract-condition/to-string.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |


## Inheritors


| Name |
|---|
| [JunctionPresentInCell](../-junction-present-in-cell/index.html) |
| [BiomolPresentInNeighbor](../-biomol-present-in-neighbor/index.html) |
| [NeighborhoodPresent](../-neighborhood-present/index.html) |

