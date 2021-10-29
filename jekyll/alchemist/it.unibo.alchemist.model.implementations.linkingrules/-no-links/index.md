---
title: NoLinks
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.linkingrules](../index.html)/[NoLinks](index.html)



# NoLinks



[jvm]\
open class [NoLinks](index.html)<[T](index.html), [P](index.html) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<[P](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html)>?> : [AbstractLocallyConsistentLinkingRule](../-abstract-locally-consistent-linking-rule/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html), [P](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html)> 

This rule guarantees that no links are created at all.



## Parameters


jvm

| | |
|---|---|
| <T> | concentration type |
| <P> | position type |



## Functions


| Name | Summary |
|---|---|
| [computeNeighborhood](compute-neighborhood.html) | [jvm]<br>fun [computeNeighborhood](compute-neighborhood.html)(center: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html)>, environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html), [P](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html)>): [Neighborhood](../../it.unibo.alchemist.model.interfaces/-neighborhood/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html)> |
| [isLocallyConsistent](../-abstract-locally-consistent-linking-rule/is-locally-consistent.html) | [jvm]<br>fun [isLocallyConsistent](../-abstract-locally-consistent-linking-rule/is-locally-consistent.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>abstract fun [isLocallyConsistent](../../it.unibo.alchemist.model.interfaces/-linking-rule/is-locally-consistent.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |

