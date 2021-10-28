//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.actions.steeringstrategies](../index.md)/[DistanceWeighted](index.md)

# DistanceWeighted

[jvm]\
class [DistanceWeighted](index.md)<[T](index.md)>(**environment**: [Euclidean2DEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-euclidean2-d-environment/index.md)<[T](index.md)>, **pedestrian**: [Pedestrian2D](../../it.unibo.alchemist.model.interfaces/-pedestrian2-d/index.md)<[T](index.md)>, **defaultWeight**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) : [Weighted](../-weighted/index.md)<[T](index.md)> 

[Weighted](../-weighted/index.md) strategy where the weight of each steering action is the inverse of the pedestrian's distance from the action's target (the closer the target, the more important the action). defaultWeight is used for actions without a target.

## Parameters

jvm

| | |
|---|---|
| environment | the environment in which the pedestrian moves. |
| pedestrian | the owner of the steering action this strategy belongs to. |

## Constructors

| | |
|---|---|
| [DistanceWeighted](-distance-weighted.md) | [jvm]<br>fun <[T](index.md)> [DistanceWeighted](-distance-weighted.md)(environment: [Euclidean2DEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-euclidean2-d-environment/index.md)<[T](index.md)>, pedestrian: [Pedestrian2D](../../it.unibo.alchemist.model.interfaces/-pedestrian2-d/index.md)<[T](index.md)>, defaultWeight: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 1.0)<br>    the environment in which the pedestrian moves. |

## Functions

| Name | Summary |
|---|---|
| [computeNextPosition](../-weighted/compute-next-position.md) | [jvm]<br>open override fun [computeNextPosition](../-weighted/compute-next-position.md)(actions: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[SteeringAction](../../it.unibo.alchemist.model.interfaces/-steering-action/index.md)<[T](index.md), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)>>): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)<br>[actions](../-weighted/compute-next-position.md) are partitioned in group steering actions and non-group steering actions. |
| [computeTarget](../-weighted/compute-target.md) | [jvm]<br>open override fun [computeTarget](../-weighted/compute-target.md)(actions: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[SteeringAction](../../it.unibo.alchemist.model.interfaces/-steering-action/index.md)<[T](index.md), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)>>): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)<br>If there's no [SteeringActionWithTarget](../../it.unibo.alchemist.model.interfaces/-steering-action-with-target/index.md) among the provided [actions](../-weighted/compute-target.md), a zero vector is returned. |
