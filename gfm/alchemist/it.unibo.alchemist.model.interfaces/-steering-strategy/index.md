//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces](../index.md)/[SteeringStrategy](index.md)

# SteeringStrategy

[jvm]\
interface [SteeringStrategy](index.md)<[T](index.md), [P](index.md) : [Position](../-position/index.md)<[P](index.md)>>

Strategy interface describing how the next points of the steering actions are combined to calculate the next position to move on.

## Functions

| Name | Summary |
|---|---|
| [computeNextPosition](compute-next-position.md) | [jvm]<br>abstract fun [computeNextPosition](compute-next-position.md)(actions: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[SteeringAction](../-steering-action/index.md)<[T](index.md), [P](index.md)>>): [P](index.md)<br>Computes the next position starting from the steering actions the pedestrian obey to, in relative coordinates with respect to its current position. |
| [computeTarget](compute-target.md) | [jvm]<br>abstract fun [computeTarget](compute-target.md)(actions: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[SteeringAction](../-steering-action/index.md)<[T](index.md), [P](index.md)>>): [P](index.md)<br>Computes the target to reach starting from the steering actions the pedestrian obey to, in absolute coordinates. |

## Inheritors

| Name |
|---|
| [Filtered](../../it.unibo.alchemist.model.implementations.actions.steeringstrategies/-filtered/index.md) |
| [Weighted](../../it.unibo.alchemist.model.implementations.actions.steeringstrategies/-weighted/index.md) |
| [PhysicalSteeringStrategy](../-physical-steering-strategy/index.md) |
