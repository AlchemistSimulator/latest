---
title: ConnectionBeam
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.linkingrules](../index.html)/[ConnectionBeam](index.html)



# ConnectionBeam



[jvm]\
class [ConnectionBeam](index.html)<[T](index.html)> : [ConnectWithinDistance](../-connect-within-distance/index.html)<[T](../../it.unibo.alchemist.model.implementations.environments/-image-environment/index.html), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)> 

Connects two nodes if, throwing a beam from one to the other, there exists at least one path entirely inside the beam that connects the two nodes. This rule is ideal for environments with obstacles, where the user wants some tolerance in connection breaking.



## Parameters


jvm

| | |
|---|---|
| <T> | concentration type |



## Constructors


| | |
|---|---|
| [ConnectionBeam](-connection-beam.html) | [jvm]<br>open fun [ConnectionBeam](-connection-beam.html)(radius: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), beamSize: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>beam maximum length |


## Functions


| Name | Summary |
|---|---|
| [computeNeighborhood](compute-neighborhood.html) | [jvm]<br>open fun [computeNeighborhood](compute-neighborhood.html)(center: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.environments/-image-environment/index.html)>, environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../../it.unibo.alchemist.model.implementations.environments/-image-environment/index.html), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)>): [Neighborhood](../../it.unibo.alchemist.model.interfaces/-neighborhood/index.html)<[T](../../it.unibo.alchemist.model.implementations.environments/-image-environment/index.html)> |
| [isLocallyConsistent](../-abstract-locally-consistent-linking-rule/is-locally-consistent.html) | [jvm]<br>fun [isLocallyConsistent](../-abstract-locally-consistent-linking-rule/is-locally-consistent.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |

