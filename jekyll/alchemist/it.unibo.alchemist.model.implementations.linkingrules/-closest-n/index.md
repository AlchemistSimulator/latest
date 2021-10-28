---
title: ClosestN
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.linkingrules](../index.html)/[ClosestN](index.html)



# ClosestN



[jvm]\
open class [ClosestN](index.html)<[T](index.html), [P](index.html) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<[P](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html)>?> : [LinkingRule](../../it.unibo.alchemist.model.interfaces/-linking-rule/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html), [P](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html)> 

Non local-consistent rule that connect the closest N nodes together. Two nodes get connected if either one belongs to the set of the ten devices closest to the other.



## Parameters


jvm

| | |
|---|---|
| <T> | Concentration type |
| <P> | [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html) type |



## Constructors


| | |
|---|---|
| [ClosestN](-closest-n.html) | [jvm]<br>open fun [ClosestN](-closest-n.html)(n: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), expectedNodes: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), maxNodes: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>neighbors |
| [ClosestN](-closest-n.html) | [jvm]<br>open fun [ClosestN](-closest-n.html)(n: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), expectedNodes: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>neighbors |
| [ClosestN](-closest-n.html) | [jvm]<br>open fun [ClosestN](-closest-n.html)(n: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>neighbors |


## Functions


| Name | Summary |
|---|---|
| [computeNeighborhood](compute-neighborhood.html) | [jvm]<br>fun [computeNeighborhood](compute-neighborhood.html)(center: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html)>, environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html), [P](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html)>): [Neighborhood](../../it.unibo.alchemist.model.interfaces/-neighborhood/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html)> |
| [isLocallyConsistent](is-locally-consistent.html) | [jvm]<br>fun [isLocallyConsistent](is-locally-consistent.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |


## Inheritors


| Name |
|---|
| [ConditionalClosestN](../-conditional-closest-n/index.html) |

