//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.actions.steeringstrategies](../index.md)/[TypeBased](index.md)

# TypeBased

[jvm]\
class [TypeBased](index.md)<[T](index.md)>(**environment**: [Euclidean2DEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-euclidean2-d-environment/index.md)<[T](index.md)>, **pedestrian**: [Pedestrian2D](../../it.unibo.alchemist.model.interfaces/-pedestrian2-d/index.md)<[T](index.md)>, **typeWeights**: [LinkedHashMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-linked-hash-map/index.html)<[KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[SteeringAction](../../it.unibo.alchemist.model.interfaces/-steering-action/index.md)<[T](index.md), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)>>, [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)>, **defaultWeight**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) : [Weighted](../-weighted/index.md)<[T](index.md)> 

A [Weighted](../-weighted/index.md) steering strategy assigning weights based on actions' types (each type has its own weight, specified by the client).

## Parameters

jvm

| | |
|---|---|
| environment | the environment in which the pedestrian moves. |
| pedestrian | the owner of the steering actions combined by this strategy. |
| typeWeights | the weight for each type of steering action. |

## Constructors

| | |
|---|---|
| [TypeBased](-type-based.md) | [jvm]<br>fun <[T](index.md)> [TypeBased](-type-based.md)(environment: [Euclidean2DEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-euclidean2-d-environment/index.md)<[T](index.md)>, pedestrian: [Pedestrian2D](../../it.unibo.alchemist.model.interfaces/-pedestrian2-d/index.md)<[T](index.md)>, typeWeights: [LinkedHashMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-linked-hash-map/index.html)<[KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[SteeringAction](../../it.unibo.alchemist.model.interfaces/-steering-action/index.md)<[T](index.md), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)>>, [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)>, defaultWeight: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 0.0)<br>    the environment in which the pedestrian moves. |

## Functions

| Name | Summary |
|---|---|
| [computeNextPosition](../-weighted/compute-next-position.md) | [jvm]<br>open override fun [computeNextPosition](../-weighted/compute-next-position.md)(actions: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[SteeringAction](../../it.unibo.alchemist.model.interfaces/-steering-action/index.md)<[T](index.md), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)>>): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)<br>[actions](../-weighted/compute-next-position.md) are partitioned in group steering actions and non-group steering actions. |
| [computeTarget](../-weighted/compute-target.md) | [jvm]<br>open override fun [computeTarget](../-weighted/compute-target.md)(actions: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[SteeringAction](../../it.unibo.alchemist.model.interfaces/-steering-action/index.md)<[T](index.md), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)>>): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)<br>If there's no [SteeringActionWithTarget](../../it.unibo.alchemist.model.interfaces/-steering-action-with-target/index.md) among the provided [actions](../-weighted/compute-target.md), a zero vector is returned. |
