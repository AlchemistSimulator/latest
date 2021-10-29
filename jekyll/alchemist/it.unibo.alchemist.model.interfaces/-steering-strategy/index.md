---
title: SteeringStrategy
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces](../index.html)/[SteeringStrategy](index.html)



# SteeringStrategy



[jvm]\
interface [SteeringStrategy](index.html)<[T](index.html), [P](index.html) : [Position](../-position/index.html)<[P](index.html)>>

Strategy interface describing how the next points of the steering actions are combined to calculate the next position to move on.



## Functions


| Name | Summary |
|---|---|
| [computeNextPosition](compute-next-position.html) | [jvm]<br>abstract fun [computeNextPosition](compute-next-position.html)(actions: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[SteeringAction](../-steering-action/index.html)<[T](index.html), [P](index.html)>>): [P](index.html)<br>Computes the next position starting from the steering actions the pedestrian obey to, in relative coordinates with respect to its current position. |
| [computeTarget](compute-target.html) | [jvm]<br>abstract fun [computeTarget](compute-target.html)(actions: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[SteeringAction](../-steering-action/index.html)<[T](index.html), [P](index.html)>>): [P](index.html)<br>Computes the target to reach starting from the steering actions the pedestrian obey to, in absolute coordinates. |


## Inheritors


| Name |
|---|
| [Filtered](../../it.unibo.alchemist.model.implementations.actions.steeringstrategies/-filtered/index.html) |
| [Weighted](../../it.unibo.alchemist.model.implementations.actions.steeringstrategies/-weighted/index.html) |
| [PhysicalSteeringStrategy](../-physical-steering-strategy/index.html) |

