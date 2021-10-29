---
title: GroupSteeringAction
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces](../index.html)/[GroupSteeringAction](index.html)



# GroupSteeringAction



[jvm]\
interface [GroupSteeringAction](index.html)<[T](index.html), [P](index.html) : [Position](../-position/index.html)<[P](index.html)>, [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html)<[P](index.html)>> : [SteeringAction](../-steering-action/index.html)<[T](index.html), [P](index.html)> 

A [SteeringAction](../-steering-action/index.html) related to a group of pedestrians.



## Functions


| Name | Summary |
|---|---|
| [cloneAction](../-steering-action-with-target/index.html#1308842947%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [cloneAction](../-steering-action-with-target/index.html#1308842947%2FFunctions%2F-134779887)(p0: [Node](../-node/index.html)<[T](index.html)>, p1: [Reaction](../-reaction/index.html)<[T](index.html)>): [Action](../-action/index.html)<[T](index.html)> |
| [execute](../-action/execute.html) | [jvm]<br>abstract fun [execute](../-action/execute.html)() |
| [getContext](../-action/get-context.html) | [jvm]<br>abstract fun [getContext](../-action/get-context.html)(): [Context](../-context/index.html) |
| [getOutboundDependencies](../-action/get-outbound-dependencies.html) | [jvm]<br>abstract fun [getOutboundDependencies](../-action/get-outbound-dependencies.html)(): ListSet<out [Dependency](../-dependency/index.html)> |
| [group](group.html) | [jvm]<br>abstract fun [group](group.html)(): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Pedestrian](../-pedestrian/index.html)<[T](index.html), [P](index.html), *>><br>The list of pedestrians influencing this action. |
| [nextPosition](../-steering-action/next-position.html) | [jvm]<br>abstract fun [nextPosition](../-steering-action/next-position.html)(): [P](index.html)<br>The position the owner of this action moves to when it is executed, in relative coordinates with respect to its current position. |


## Inheritors


| Name |
|---|
| [AbstractGroupSteeringAction](../../it.unibo.alchemist.model.implementations.actions/-abstract-group-steering-action/index.html) |

