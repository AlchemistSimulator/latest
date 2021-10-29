---
title: DistanceWeighted
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.actions.steeringstrategies](../index.html)/[DistanceWeighted](index.html)



# DistanceWeighted



[jvm]\
class [DistanceWeighted](index.html)<[T](index.html)>(**environment**: [Euclidean2DEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-euclidean2-d-environment/index.html)<[T](index.html)>, **pedestrian**: [Pedestrian2D](../../it.unibo.alchemist.model.interfaces/-pedestrian2-d/index.html)<[T](index.html)>, **defaultWeight**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) : [Weighted](../-weighted/index.html)<[T](index.html)> 

[Weighted](../-weighted/index.html) strategy where the weight of each steering action is the inverse of the pedestrian's distance from the action's target (the closer the target, the more important the action). defaultWeight is used for actions without a target.



## Parameters


jvm

| | |
|---|---|
| environment | the environment in which the pedestrian moves. |
| pedestrian | the owner of the steering action this strategy belongs to. |



## Constructors


| | |
|---|---|
| [DistanceWeighted](-distance-weighted.html) | [jvm]<br>fun <[T](index.html)> [DistanceWeighted](-distance-weighted.html)(environment: [Euclidean2DEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-euclidean2-d-environment/index.html)<[T](index.html)>, pedestrian: [Pedestrian2D](../../it.unibo.alchemist.model.interfaces/-pedestrian2-d/index.html)<[T](index.html)>, defaultWeight: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 1.0)<br>    the environment in which the pedestrian moves. |


## Functions


| Name | Summary |
|---|---|
| [computeNextPosition](../-weighted/compute-next-position.html) | [jvm]<br>open override fun [computeNextPosition](../-weighted/compute-next-position.html)(actions: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[SteeringAction](../../it.unibo.alchemist.model.interfaces/-steering-action/index.html)<[T](index.html), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)>>): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)<br>[actions](../-weighted/compute-next-position.html) are partitioned in group steering actions and non-group steering actions. |
| [computeTarget](../-weighted/compute-target.html) | [jvm]<br>open override fun [computeTarget](../-weighted/compute-target.html)(actions: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[SteeringAction](../../it.unibo.alchemist.model.interfaces/-steering-action/index.html)<[T](index.html), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)>>): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)<br>If there's no [SteeringActionWithTarget](../../it.unibo.alchemist.model.interfaces/-steering-action-with-target/index.html) among the provided [actions](../-weighted/compute-target.html), a zero vector is returned. |

