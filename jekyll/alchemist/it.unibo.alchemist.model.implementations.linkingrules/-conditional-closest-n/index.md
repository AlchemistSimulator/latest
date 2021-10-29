---
title: ConditionalClosestN
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.linkingrules](../index.html)/[ConditionalClosestN](index.html)



# ConditionalClosestN



[jvm]\
class [ConditionalClosestN](index.html)<[T](index.html), [P](index.html) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<[P](../../it.unibo.alchemist.model.interfaces/-route/index.html)>?> : [ClosestN](../-closest-n/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html), [P](../../it.unibo.alchemist.model.interfaces/-route/index.html)> 

A [ClosestN](../-closest-n/index.html) rule that also checks that a [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html) has a specific concentration before allowing the connection.



## Parameters


jvm

| | |
|---|---|
| <T> | Concentration type |
| <P> | [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html) type |



## Constructors


| | |
|---|---|
| [ConditionalClosestN](-conditional-closest-n.html) | [jvm]<br>open fun [ConditionalClosestN](-conditional-closest-n.html)(n: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), expectedNodes: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), mol: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html), value: [T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html))<br>number of neighbors |
| [ConditionalClosestN](-conditional-closest-n.html) | [jvm]<br>open fun [ConditionalClosestN](-conditional-closest-n.html)(n: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), mol: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html), value: [T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html))<br>number of neighbors |


## Functions


| Name | Summary |
|---|---|
| [computeNeighborhood](../-closest-n/compute-neighborhood.html) | [jvm]<br>fun [computeNeighborhood](../-closest-n/compute-neighborhood.html)(center: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html)>, environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html), [P](../../it.unibo.alchemist.model.interfaces/-route/index.html)>): [Neighborhood](../../it.unibo.alchemist.model.interfaces/-neighborhood/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html)><br>abstract fun [computeNeighborhood](../../it.unibo.alchemist.model.interfaces/-linking-rule/compute-neighborhood.html)(p: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html)>, p1: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html), [P](../../it.unibo.alchemist.model.interfaces/-route/index.html)>): [Neighborhood](../../it.unibo.alchemist.model.interfaces/-neighborhood/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html)> |
| [isLocallyConsistent](../-closest-n/is-locally-consistent.html) | [jvm]<br>fun [isLocallyConsistent](../-closest-n/is-locally-consistent.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>abstract fun [isLocallyConsistent](../../it.unibo.alchemist.model.interfaces/-linking-rule/is-locally-consistent.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |

