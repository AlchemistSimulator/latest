---
title: FullyConnected
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.linkingrules](../index.html)/[FullyConnected](index.html)



# FullyConnected



[jvm]\
class [FullyConnected](index.html)<[T](index.html), [P](index.html) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<[P](index.html)>> : [LinkingRule](../../it.unibo.alchemist.model.interfaces/-linking-rule/index.html)<[T](index.html), [P](index.html)> 

This rule connects each and every node to each and every other.



## Constructors


| | |
|---|---|
| [FullyConnected](-fully-connected.html) | [jvm]<br>fun [FullyConnected](-fully-connected.html)() |


## Functions


| Name | Summary |
|---|---|
| [computeNeighborhood](compute-neighborhood.html) | [jvm]<br>open override fun [computeNeighborhood](compute-neighborhood.html)(center: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](index.html)>, environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](index.html), [P](index.html)>): [Neighborhood](../../it.unibo.alchemist.model.interfaces/-neighborhood/index.html)<[T](index.html)> |
| [isLocallyConsistent](is-locally-consistent.html) | [jvm]<br>open override fun [isLocallyConsistent](is-locally-consistent.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |

