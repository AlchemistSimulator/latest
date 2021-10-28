---
title: LinkNodesWithinRoutingRange
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.linkingrules](../index.html)/[LinkNodesWithinRoutingRange](index.html)



# LinkNodesWithinRoutingRange



[jvm]\
class [LinkNodesWithinRoutingRange](index.html)<[T](index.html)> : [AbstractLocallyConsistentLinkingRule](../-abstract-locally-consistent-linking-rule/index.html)<[T](index.html), [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)>



## Parameters


jvm

| | |
|---|---|
| <T> | concentration type |



## Constructors


| | |
|---|---|
| [LinkNodesWithinRoutingRange](-link-nodes-within-routing-range.html) | [jvm]<br>open fun [LinkNodesWithinRoutingRange](-link-nodes-within-routing-range.html)(r: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>range |


## Functions


| Name | Summary |
|---|---|
| [computeNeighborhood](compute-neighborhood.html) | [jvm]<br>open fun [computeNeighborhood](compute-neighborhood.html)(center: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](index.html)>, environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](index.html), [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)>): [Neighborhood](../../it.unibo.alchemist.model.interfaces/-neighborhood/index.html)<[T](index.html)> |
| [isLocallyConsistent](../-abstract-locally-consistent-linking-rule/is-locally-consistent.html) | [jvm]<br>fun [isLocallyConsistent](../-abstract-locally-consistent-linking-rule/is-locally-consistent.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |

