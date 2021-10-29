---
title: computeNextPosition
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.actions.steeringstrategies](../index.html)/[Weighted](index.html)/[computeNextPosition](compute-next-position.html)



# computeNextPosition



[jvm]\
open override fun [computeNextPosition](compute-next-position.html)(actions: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[SteeringAction](../../it.unibo.alchemist.model.interfaces/-steering-action/index.html)<[T](index.html), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)>>): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)



[actions](compute-next-position.html) are partitioned in group steering actions and non-group steering actions. The overall next position for each of these two sets of actions is computed via weighted sum. The resulting vectors are then summed together (with unitary weight).




