---
title: Nearest
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.actions.steeringstrategies](../index.html)/[Nearest](index.html)



# Nearest



[jvm]\
class [Nearest](index.html)<[T](index.html)>(**environment**: [Euclidean2DEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-euclidean2-d-environment/index.html)<[T](index.html)>, **pedestrian**: [Pedestrian2D](../../it.unibo.alchemist.model.interfaces/-pedestrian2-d/index.html)<[T](index.html)>) : [Filtered](../-filtered/index.html)<[T](index.html), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)> 

[Filtered](../-filtered/index.html) strategy considering only the group steering action and the non-group steering action whose targets are nearest to the pedestrian's position. The two actions are combined using [DistanceWeighted](../-distance-weighted/index.html) strategy.



## Parameters


jvm

| | |
|---|---|
| environment | the environment in which the pedestrian moves. |
| pedestrian | the owner of the steering action this strategy belongs to. |



## Constructors


| | |
|---|---|
| [Nearest](-nearest.html) | [jvm]<br>fun <[T](index.html)> [Nearest](-nearest.html)(environment: [Euclidean2DEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-euclidean2-d-environment/index.html)<[T](index.html)>, pedestrian: [Pedestrian2D](../../it.unibo.alchemist.model.interfaces/-pedestrian2-d/index.html)<[T](index.html)>)<br>    the environment in which the pedestrian moves. |


## Functions


| Name | Summary |
|---|---|
| [computeNextPosition](index.html#-347208095%2FFunctions%2F-134779887) | [jvm]<br>open override fun [computeNextPosition](index.html#-347208095%2FFunctions%2F-134779887)(actions: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[SteeringAction](../../it.unibo.alchemist.model.interfaces/-steering-action/index.html)<[T](index.html), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)>>): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)<br>Delegated to steerStrategy after [filter](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/index.html)ing the given [actions](index.html#-347208095%2FFunctions%2F-134779887). |
| [computeTarget](index.html#1755807273%2FFunctions%2F-134779887) | [jvm]<br>open override fun [computeTarget](index.html#1755807273%2FFunctions%2F-134779887)(actions: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[SteeringAction](../../it.unibo.alchemist.model.interfaces/-steering-action/index.html)<[T](index.html), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)>>): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)<br>Computes the target to reach starting from the steering actions the pedestrian obey to, in absolute coordinates. |

