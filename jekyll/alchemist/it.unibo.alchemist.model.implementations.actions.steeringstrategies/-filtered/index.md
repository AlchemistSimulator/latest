---
title: Filtered
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.actions.steeringstrategies](../index.html)/[Filtered](index.html)



# Filtered



[jvm]\
open class [Filtered](index.html)<[T](index.html), [P](index.html) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<[P](index.html)>, [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html)<[P](index.html)>>(**steerStrategy**: [SteeringStrategy](../../it.unibo.alchemist.model.interfaces/-steering-strategy/index.html)<[T](index.html), [P](index.html)>, **filter**: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[SteeringAction](../../it.unibo.alchemist.model.interfaces/-steering-action/index.html)<[T](index.html), [P](index.html)>>.() -> [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[SteeringAction](../../it.unibo.alchemist.model.interfaces/-steering-action/index.html)<[T](index.html), [P](index.html)>>) : [SteeringStrategy](../../it.unibo.alchemist.model.interfaces/-steering-strategy/index.html)<[T](index.html), [P](index.html)> 

[SteeringStrategy](../../it.unibo.alchemist.model.interfaces/-steering-strategy/index.html) decorator applying a filter to the list of steering actions (see [computeNextPosition](compute-next-position.html)).



## Parameters


jvm

| | |
|---|---|
| steerStrategy | computeNextPosition is delegated to this strategy. |
| filter | the filter to apply on the list of steering actions. |



## Constructors


| | |
|---|---|
| [Filtered](-filtered.html) | [jvm]<br>fun <[T](index.html), [P](index.html) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<[P](index.html)>, [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html)<[P](index.html)>> [Filtered](-filtered.html)(steerStrategy: [SteeringStrategy](../../it.unibo.alchemist.model.interfaces/-steering-strategy/index.html)<[T](index.html), [P](index.html)>, filter: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[SteeringAction](../../it.unibo.alchemist.model.interfaces/-steering-action/index.html)<[T](index.html), [P](index.html)>>.() -> [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[SteeringAction](../../it.unibo.alchemist.model.interfaces/-steering-action/index.html)<[T](index.html), [P](index.html)>>)<br>    computeNextPosition is delegated to this strategy. |


## Functions


| Name | Summary |
|---|---|
| [computeNextPosition](compute-next-position.html) | [jvm]<br>open override fun [computeNextPosition](compute-next-position.html)(actions: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[SteeringAction](../../it.unibo.alchemist.model.interfaces/-steering-action/index.html)<[T](index.html), [P](index.html)>>): [P](index.html)<br>Delegated to steerStrategy after [filter](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/index.html)ing the given [actions](compute-next-position.html). |
| [computeTarget](index.html#1254770434%2FFunctions%2F-134779887) | [jvm]<br>open override fun [computeTarget](index.html#1254770434%2FFunctions%2F-134779887)(actions: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[SteeringAction](../../it.unibo.alchemist.model.interfaces/-steering-action/index.html)<[T](index.html), [P](index.html)>>): [P](index.html)<br>Computes the target to reach starting from the steering actions the pedestrian obey to, in absolute coordinates. |


## Inheritors


| Name |
|---|
| [Nearest](../-nearest/index.html) |

