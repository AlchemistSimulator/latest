---
title: Weighted
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.actions.steeringstrategies](../index.html)/[Weighted](index.html)



# Weighted



[jvm]\
open class [Weighted](index.html)<[T](index.html)>(**environment**: [Euclidean2DEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-euclidean2-d-environment/index.html)<[T](index.html)>, **pedestrian**: [Pedestrian2D](../../it.unibo.alchemist.model.interfaces/-pedestrian2-d/index.html)<[T](index.html)>, **weight**: [SteeringAction](../../it.unibo.alchemist.model.interfaces/-steering-action/index.html)<[T](index.html), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)>.() -> [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) : [SteeringStrategy](../../it.unibo.alchemist.model.interfaces/-steering-strategy/index.html)<[T](index.html), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)> 

A [SteeringStrategy](../../it.unibo.alchemist.model.interfaces/-steering-strategy/index.html) performing a weighted sum of steering actions (see [computeNextPosition](compute-next-position.html)).



## Parameters


jvm

| | |
|---|---|
| environment | the environment in which the pedestrian moves. |
| pedestrian | the owner of the steering actions combined by this strategy. |
| weight | lambda used to assign a weight to each steering action: the higher the weight, the greater the     importance of the action. |



## Constructors


| | |
|---|---|
| [Weighted](-weighted.html) | [jvm]<br>fun <[T](index.html)> [Weighted](-weighted.html)(environment: [Euclidean2DEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-euclidean2-d-environment/index.html)<[T](index.html)>, pedestrian: [Pedestrian2D](../../it.unibo.alchemist.model.interfaces/-pedestrian2-d/index.html)<[T](index.html)>, weight: [SteeringAction](../../it.unibo.alchemist.model.interfaces/-steering-action/index.html)<[T](index.html), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)>.() -> [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>    the environment in which the pedestrian moves. |


## Functions


| Name | Summary |
|---|---|
| [computeNextPosition](compute-next-position.html) | [jvm]<br>open override fun [computeNextPosition](compute-next-position.html)(actions: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[SteeringAction](../../it.unibo.alchemist.model.interfaces/-steering-action/index.html)<[T](index.html), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)>>): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)<br>[actions](compute-next-position.html) are partitioned in group steering actions and non-group steering actions. |
| [computeTarget](compute-target.html) | [jvm]<br>open override fun [computeTarget](compute-target.html)(actions: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[SteeringAction](../../it.unibo.alchemist.model.interfaces/-steering-action/index.html)<[T](index.html), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)>>): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)<br>If there's no [SteeringActionWithTarget](../../it.unibo.alchemist.model.interfaces/-steering-action-with-target/index.html) among the provided [actions](compute-target.html), a zero vector is returned. |


## Inheritors


| Name |
|---|
| [DistanceWeighted](../-distance-weighted/index.html) |
| [SinglePrevalent](../-single-prevalent/index.html) |
| [TypeBased](../-type-based/index.html) |

