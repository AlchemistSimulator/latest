---
title: AbstractLocallyConsistentLinkingRule
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.linkingrules](../index.html)/[AbstractLocallyConsistentLinkingRule](index.html)



# AbstractLocallyConsistentLinkingRule



[jvm]\
abstract class [AbstractLocallyConsistentLinkingRule](index.html)<[T](index.html), [P](index.html) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<out [P](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)>?> : [LinkingRule](../../it.unibo.alchemist.model.interfaces/-linking-rule/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html), [P](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)>



## Parameters


jvm

| | |
|---|---|
| <T> | Concentration type |
| <P> | [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html) type |



## Functions


| Name | Summary |
|---|---|
| [computeNeighborhood](../../it.unibo.alchemist.model.interfaces/-linking-rule/compute-neighborhood.html) | [jvm]<br>abstract fun [computeNeighborhood](../../it.unibo.alchemist.model.interfaces/-linking-rule/compute-neighborhood.html)(p: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)>, p1: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html), [P](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)>): [Neighborhood](../../it.unibo.alchemist.model.interfaces/-neighborhood/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)> |
| [isLocallyConsistent](is-locally-consistent.html) | [jvm]<br>fun [isLocallyConsistent](is-locally-consistent.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |


## Inheritors


| Name |
|---|
| [NoLinks](../-no-links/index.html) |
| [ConnectWithinDistance](../-connect-within-distance/index.html) |
| [LinkNodesWithinRoutingRange](../-link-nodes-within-routing-range/index.html) |

