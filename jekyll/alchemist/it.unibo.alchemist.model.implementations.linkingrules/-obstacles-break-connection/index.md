---
title: ObstaclesBreakConnection
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.linkingrules](../index.html)/[ObstaclesBreakConnection](index.html)



# ObstaclesBreakConnection



[jvm]\
class [ObstaclesBreakConnection](index.html)<[T](index.html), [P](index.html) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<[P](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)>?, [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html)<[P](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)>?> : [ConnectWithinDistance](../-connect-within-distance/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html), [P](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)> 

Similar to [ConnectWithinDistance](../-connect-within-distance/index.html), but if the environment has obstacles, the links are removed.



## Parameters


jvm

| | |
|---|---|
| <P> | position type |
| <T> | concentration type |



## Constructors


| | |
|---|---|
| [ObstaclesBreakConnection](-obstacles-break-connection.html) | [jvm]<br>open fun [ObstaclesBreakConnection](-obstacles-break-connection.html)(radius: [Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html))<br>connection range |


## Functions


| Name | Summary |
|---|---|
| [computeNeighborhood](compute-neighborhood.html) | [jvm]<br>open fun [computeNeighborhood](compute-neighborhood.html)(center: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)>, env: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html), [P](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)>): [Neighborhood](../../it.unibo.alchemist.model.interfaces/-neighborhood/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)><br>Subclasses may change the way a neighborhood is computed.<br>[jvm]<br>abstract fun [computeNeighborhood](../../it.unibo.alchemist.model.interfaces/-linking-rule/compute-neighborhood.html)(p: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)>, p1: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html), [P](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)>): [Neighborhood](../../it.unibo.alchemist.model.interfaces/-neighborhood/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)> |
| [isLocallyConsistent](../-abstract-locally-consistent-linking-rule/is-locally-consistent.html) | [jvm]<br>fun [isLocallyConsistent](../-abstract-locally-consistent-linking-rule/is-locally-consistent.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>abstract fun [isLocallyConsistent](../../it.unibo.alchemist.model.interfaces/-linking-rule/is-locally-consistent.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |

