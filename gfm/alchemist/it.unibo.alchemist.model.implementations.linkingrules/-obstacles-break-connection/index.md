//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.linkingrules](../index.md)/[ObstaclesBreakConnection](index.md)

# ObstaclesBreakConnection

[jvm]\
class [ObstaclesBreakConnection](index.md)<[T](index.md), [P](index.md) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<[P](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.md)>?, [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.md)<[P](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.md)>?> : [ConnectWithinDistance](../-connect-within-distance/index.md)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.md), [P](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.md)> 

Similar to [ConnectWithinDistance](../-connect-within-distance/index.md), but if the environment has obstacles, the links are removed.

## Parameters

jvm

| | |
|---|---|
| <P> | position type |
| <T> | concentration type |

## Constructors

| | |
|---|---|
| [ObstaclesBreakConnection](-obstacles-break-connection.md) | [jvm]<br>open fun [ObstaclesBreakConnection](-obstacles-break-connection.md)(radius: [Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html))<br>connection range |

## Functions

| Name | Summary |
|---|---|
| [computeNeighborhood](compute-neighborhood.md) | [jvm]<br>open fun [computeNeighborhood](compute-neighborhood.md)(center: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.md)>, env: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.md), [P](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.md)>): [Neighborhood](../../it.unibo.alchemist.model.interfaces/-neighborhood/index.md)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.md)><br>Subclasses may change the way a neighborhood is computed.<br>[jvm]<br>abstract fun [computeNeighborhood](../../it.unibo.alchemist.model.interfaces/-linking-rule/compute-neighborhood.md)(p: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.md)>, p1: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.md), [P](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.md)>): [Neighborhood](../../it.unibo.alchemist.model.interfaces/-neighborhood/index.md)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.md)> |
| [isLocallyConsistent](../-abstract-locally-consistent-linking-rule/is-locally-consistent.md) | [jvm]<br>fun [isLocallyConsistent](../-abstract-locally-consistent-linking-rule/is-locally-consistent.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>abstract fun [isLocallyConsistent](../../it.unibo.alchemist.model.interfaces/-linking-rule/is-locally-consistent.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
