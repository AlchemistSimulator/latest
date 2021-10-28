//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.actions.steeringstrategies](../index.md)/[Filtered](index.md)

# Filtered

[jvm]\
open class [Filtered](index.md)<[T](index.md), [P](index.md) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<[P](index.md)>, [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.md)<[P](index.md)>>(**steerStrategy**: [SteeringStrategy](../../it.unibo.alchemist.model.interfaces/-steering-strategy/index.md)<[T](index.md), [P](index.md)>, **filter**: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[SteeringAction](../../it.unibo.alchemist.model.interfaces/-steering-action/index.md)<[T](index.md), [P](index.md)>>.() -> [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[SteeringAction](../../it.unibo.alchemist.model.interfaces/-steering-action/index.md)<[T](index.md), [P](index.md)>>) : [SteeringStrategy](../../it.unibo.alchemist.model.interfaces/-steering-strategy/index.md)<[T](index.md), [P](index.md)> 

[SteeringStrategy](../../it.unibo.alchemist.model.interfaces/-steering-strategy/index.md) decorator applying a filter to the list of steering actions (see [computeNextPosition](compute-next-position.md)).

## Parameters

jvm

| | |
|---|---|
| steerStrategy | computeNextPosition is delegated to this strategy. |
| filter | the filter to apply on the list of steering actions. |

## Constructors

| | |
|---|---|
| [Filtered](-filtered.md) | [jvm]<br>fun <[T](index.md), [P](index.md) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<[P](index.md)>, [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.md)<[P](index.md)>> [Filtered](-filtered.md)(steerStrategy: [SteeringStrategy](../../it.unibo.alchemist.model.interfaces/-steering-strategy/index.md)<[T](index.md), [P](index.md)>, filter: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[SteeringAction](../../it.unibo.alchemist.model.interfaces/-steering-action/index.md)<[T](index.md), [P](index.md)>>.() -> [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[SteeringAction](../../it.unibo.alchemist.model.interfaces/-steering-action/index.md)<[T](index.md), [P](index.md)>>)<br>    computeNextPosition is delegated to this strategy. |

## Functions

| Name | Summary |
|---|---|
| [computeNextPosition](compute-next-position.md) | [jvm]<br>open override fun [computeNextPosition](compute-next-position.md)(actions: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[SteeringAction](../../it.unibo.alchemist.model.interfaces/-steering-action/index.md)<[T](index.md), [P](index.md)>>): [P](index.md)<br>Delegated to steerStrategy after [filter](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/index.html)ing the given [actions](compute-next-position.md). |
| [computeTarget](index.md#1254770434%2FFunctions%2F-267951372) | [jvm]<br>open override fun [computeTarget](index.md#1254770434%2FFunctions%2F-267951372)(actions: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[SteeringAction](../../it.unibo.alchemist.model.interfaces/-steering-action/index.md)<[T](index.md), [P](index.md)>>): [P](index.md)<br>Computes the target to reach starting from the steering actions the pedestrian obey to, in absolute coordinates. |

## Inheritors

| Name |
|---|
| [Nearest](../-nearest/index.md) |
