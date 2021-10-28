//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.actions.steeringstrategies](../index.md)/[Nearest](index.md)

# Nearest

[jvm]\
class [Nearest](index.md)<[T](index.md)>(**environment**: [Euclidean2DEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-euclidean2-d-environment/index.md)<[T](index.md)>, **pedestrian**: [Pedestrian2D](../../it.unibo.alchemist.model.interfaces/-pedestrian2-d/index.md)<[T](index.md)>) : [Filtered](../-filtered/index.md)<[T](index.md), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)> 

[Filtered](../-filtered/index.md) strategy considering only the group steering action and the non-group steering action whose targets are nearest to the pedestrian's position. The two actions are combined using [DistanceWeighted](../-distance-weighted/index.md) strategy.

## Parameters

jvm

| | |
|---|---|
| environment | the environment in which the pedestrian moves. |
| pedestrian | the owner of the steering action this strategy belongs to. |

## Constructors

| | |
|---|---|
| [Nearest](-nearest.md) | [jvm]<br>fun <[T](index.md)> [Nearest](-nearest.md)(environment: [Euclidean2DEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-euclidean2-d-environment/index.md)<[T](index.md)>, pedestrian: [Pedestrian2D](../../it.unibo.alchemist.model.interfaces/-pedestrian2-d/index.md)<[T](index.md)>)<br>    the environment in which the pedestrian moves. |

## Functions

| Name | Summary |
|---|---|
| [computeNextPosition](index.md#-347208095%2FFunctions%2F-267951372) | [jvm]<br>open override fun [computeNextPosition](index.md#-347208095%2FFunctions%2F-267951372)(actions: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[SteeringAction](../../it.unibo.alchemist.model.interfaces/-steering-action/index.md)<[T](index.md), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)>>): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)<br>Delegated to steerStrategy after [filter](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/index.html)ing the given [actions](index.md#-347208095%2FFunctions%2F-267951372). |
| [computeTarget](index.md#1755807273%2FFunctions%2F-267951372) | [jvm]<br>open override fun [computeTarget](index.md#1755807273%2FFunctions%2F-267951372)(actions: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[SteeringAction](../../it.unibo.alchemist.model.interfaces/-steering-action/index.md)<[T](index.md), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)>>): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)<br>Computes the target to reach starting from the steering actions the pedestrian obey to, in absolute coordinates. |
