---
title: ConnectWithinDistance
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.linkingrules](../index.html)/[ConnectWithinDistance](index.html)



# ConnectWithinDistance



[jvm]\
open class [ConnectWithinDistance](index.html)<[T](index.html), [P](index.html) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<[P](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html)>?> : [AbstractLocallyConsistentLinkingRule](../-abstract-locally-consistent-linking-rule/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html), [P](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html)> 

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
| [ConnectWithinDistance](-connect-within-distance.html) | [jvm]<br>open fun [ConnectWithinDistance](-connect-within-distance.html)(radius: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>connection radius |


## Functions


| Name | Summary |
|---|---|
| [computeNeighborhood](compute-neighborhood.html) | [jvm]<br>open fun [computeNeighborhood](compute-neighborhood.html)(center: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html)>, environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html), [P](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html)>): [Neighborhood](../../it.unibo.alchemist.model.interfaces/-neighborhood/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html)><br>Subclasses may change the way a neighborhood is computed. |
| [isLocallyConsistent](../-abstract-locally-consistent-linking-rule/is-locally-consistent.html) | [jvm]<br>fun [isLocallyConsistent](../-abstract-locally-consistent-linking-rule/is-locally-consistent.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>abstract fun [isLocallyConsistent](../../it.unibo.alchemist.model.interfaces/-linking-rule/is-locally-consistent.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |


## Inheritors


| Name |
|---|
| [ConnectionBeam](../-connection-beam/index.html) |
| [AdaptiveRange](../-adaptive-range/index.html) |
| [ObstaclesBreakConnection](../-obstacles-break-connection/index.html) |
| [ConnectToAccessPoint](../-connect-to-access-point/index.html) |
| [ConnectViaAccessPoint](../-connect-via-access-point/index.html) |

