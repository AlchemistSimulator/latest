//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.linkingrules](../index.md)/[ConnectWithinDistance](index.md)

# ConnectWithinDistance

[jvm]\
open class [ConnectWithinDistance](index.md)<[T](index.md), [P](index.md) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<[P](../../it.unibo.alchemist.model.interfaces/-route/index.md)>?> : [AbstractLocallyConsistentLinkingRule](../-abstract-locally-consistent-linking-rule/index.md)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.md), [P](../../it.unibo.alchemist.model.interfaces/-route/index.md)> 

LinkingRule which connects nodes whose euclidean distance is shorter than a given radius.

## Parameters

jvm

| | |
|---|---|
| <T> | The type which describes the concentration of a molecule |
| <P> |  |

## Constructors

| | |
|---|---|
| [ConnectWithinDistance](-connect-within-distance.md) | [jvm]<br>open fun [ConnectWithinDistance](-connect-within-distance.md)(radius: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>connection radius |

## Functions

| Name | Summary |
|---|---|
| [computeNeighborhood](compute-neighborhood.md) | [jvm]<br>open fun [computeNeighborhood](compute-neighborhood.md)(center: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.md)>, environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.md), [P](../../it.unibo.alchemist.model.interfaces/-route/index.md)>): [Neighborhood](../../it.unibo.alchemist.model.interfaces/-neighborhood/index.md)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.md)><br>Subclasses may change the way a neighborhood is computed. |
| [isLocallyConsistent](../-abstract-locally-consistent-linking-rule/is-locally-consistent.md) | [jvm]<br>fun [isLocallyConsistent](../-abstract-locally-consistent-linking-rule/is-locally-consistent.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>abstract fun [isLocallyConsistent](../../it.unibo.alchemist.model.interfaces/-linking-rule/is-locally-consistent.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |

## Inheritors

| Name |
|---|
| [ConnectionBeam](../-connection-beam/index.md) |
| [AdaptiveRange](../-adaptive-range/index.md) |
| [ObstaclesBreakConnection](../-obstacles-break-connection/index.md) |
| [ConnectToAccessPoint](../-connect-to-access-point/index.md) |
| [ConnectViaAccessPoint](../-connect-via-access-point/index.md) |
