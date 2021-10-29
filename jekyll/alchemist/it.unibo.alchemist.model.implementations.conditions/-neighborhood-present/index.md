---
title: NeighborhoodPresent
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.conditions](../index.html)/[NeighborhoodPresent](index.html)



# NeighborhoodPresent



[jvm]\
class [NeighborhoodPresent](index.html)<[T](index.html)> : [AbstractNeighborCondition](../-abstract-neighbor-condition/index.html)<[T](../../it.unibo.alchemist.model.implementations.nodes/-abstract-node/index.html)> 

A condition is valid if the node has a neighborhood, formally if the node has at least one node connected by a linking rule.



## Parameters


jvm

| | |
|---|---|
| <T> | The concentration type. |



## Constructors


| | |
|---|---|
| [NeighborhoodPresent](-neighborhood-present.html) | [jvm]<br>open fun [NeighborhoodPresent](-neighborhood-present.html)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../../it.unibo.alchemist.model.implementations.nodes/-abstract-node/index.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.nodes/-abstract-node/index.html)>)<br>Create the condition. |


## Functions


| Name | Summary |
|---|---|
| [cloneCondition](../-abstract-condition/clone-condition.html) | [jvm]<br>open fun [cloneCondition](../-abstract-condition/clone-condition.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.nodes/-abstract-node/index.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist.model.implementations.nodes/-abstract-node/index.html)>): [Condition](../../it.unibo.alchemist.model.interfaces/-condition/index.html)<[T](../../it.unibo.alchemist.model.implementations.nodes/-abstract-node/index.html)><br>open fun [cloneCondition](clone-condition.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.nodes/-abstract-node/index.html)>, r: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist.model.implementations.nodes/-abstract-node/index.html)>): [NeighborhoodPresent](index.html)<[T](../../it.unibo.alchemist.model.implementations.nodes/-abstract-node/index.html)> |
| [getContext](../-abstract-neighbor-condition/get-context.html) | [jvm]<br>fun [getContext](../-abstract-neighbor-condition/get-context.html)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.html)<br>abstract fun [getContext](../../it.unibo.alchemist.model.interfaces/-condition/get-context.html)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.html) |
| [getInboundDependencies](../-abstract-condition/get-inbound-dependencies.html) | [jvm]<br>fun [getInboundDependencies](../-abstract-condition/get-inbound-dependencies.html)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)> |
| [getNode](../-lsa-standard-condition/index.html#-1460695024%2FFunctions%2F-134779887) | [jvm]<br>open fun [getNode](../-lsa-standard-condition/index.html#-1460695024%2FFunctions%2F-134779887)(): [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.nodes/-abstract-node/index.html)> |
| [getPropensityContribution](../-abstract-neighbor-condition/get-propensity-contribution.html) | [jvm]<br>open fun [getPropensityContribution](../-abstract-neighbor-condition/get-propensity-contribution.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Override if desired behavior differs.<br>[jvm]<br>abstract fun [getPropensityContribution](../../it.unibo.alchemist.model.interfaces/-condition/get-propensity-contribution.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getValidNeighbors](../-abstract-neighbor-condition/get-valid-neighbors.html) | [jvm]<br>fun [getValidNeighbors](../-abstract-neighbor-condition/get-valid-neighbors.html)(): [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<[Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.nodes/-abstract-node/index.html)>, [Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)><br>Searches in the given neighborhood which nodes satisfy the condition, and returns a list of valid neighbors. |
| [isValid](is-valid.html) | [jvm]<br>open fun [isValid](is-valid.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [reactionReady](../../it.unibo.alchemist.model.interfaces/-condition/reaction-ready.html) | [jvm]<br>open fun [reactionReady](../../it.unibo.alchemist.model.interfaces/-condition/reaction-ready.html)() |
| [toString](to-string.html) | [jvm]<br>open fun [toString](to-string.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |

