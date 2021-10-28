//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.actions.steeringstrategies](../index.md)/[Weighted](index.md)

# Weighted

[jvm]\
open class [Weighted](index.md)<[T](index.md)>(**environment**: [Euclidean2DEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-euclidean2-d-environment/index.md)<[T](index.md)>, **pedestrian**: [Pedestrian2D](../../it.unibo.alchemist.model.interfaces/-pedestrian2-d/index.md)<[T](index.md)>, **weight**: [SteeringAction](../../it.unibo.alchemist.model.interfaces/-steering-action/index.md)<[T](index.md), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)>.() -> [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) : [SteeringStrategy](../../it.unibo.alchemist.model.interfaces/-steering-strategy/index.md)<[T](index.md), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)> 

A [SteeringStrategy](../../it.unibo.alchemist.model.interfaces/-steering-strategy/index.md) performing a weighted sum of steering actions (see [computeNextPosition](compute-next-position.md)).

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
| [Weighted](-weighted.md) | [jvm]<br>fun <[T](index.md)> [Weighted](-weighted.md)(environment: [Euclidean2DEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-euclidean2-d-environment/index.md)<[T](index.md)>, pedestrian: [Pedestrian2D](../../it.unibo.alchemist.model.interfaces/-pedestrian2-d/index.md)<[T](index.md)>, weight: [SteeringAction](../../it.unibo.alchemist.model.interfaces/-steering-action/index.md)<[T](index.md), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)>.() -> [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>    the environment in which the pedestrian moves. |

## Functions

| Name | Summary |
|---|---|
| [computeNextPosition](compute-next-position.md) | [jvm]<br>open override fun [computeNextPosition](compute-next-position.md)(actions: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[SteeringAction](../../it.unibo.alchemist.model.interfaces/-steering-action/index.md)<[T](index.md), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)>>): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)<br>[actions](compute-next-position.md) are partitioned in group steering actions and non-group steering actions. |
| [computeTarget](compute-target.md) | [jvm]<br>open override fun [computeTarget](compute-target.md)(actions: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[SteeringAction](../../it.unibo.alchemist.model.interfaces/-steering-action/index.md)<[T](index.md), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)>>): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)<br>If there's no [SteeringActionWithTarget](../../it.unibo.alchemist.model.interfaces/-steering-action-with-target/index.md) among the provided [actions](compute-target.md), a zero vector is returned. |

## Inheritors

| Name |
|---|
| [DistanceWeighted](../-distance-weighted/index.md) |
| [SinglePrevalent](../-single-prevalent/index.md) |
| [TypeBased](../-type-based/index.md) |
