---
title: SteeringAction
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces](../index.html)/[SteeringAction](index.html)



# SteeringAction



[jvm]\
interface [SteeringAction](index.html)<[T](index.html), [P](index.html) : [Position](../-position/index.html)<[P](index.html)>> : [Action](../-action/index.html)<[T](index.html)> 

Action whose purpose is moving a node inside the environment it is in.



## Functions


| Name | Summary |
|---|---|
| [cloneAction](../-steering-action-with-target/index.html#1308842947%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [cloneAction](../-steering-action-with-target/index.html#1308842947%2FFunctions%2F-134779887)(p0: [Node](../-node/index.html)<[T](index.html)>, p1: [Reaction](../-reaction/index.html)<[T](index.html)>): [Action](../-action/index.html)<[T](index.html)> |
| [execute](../-action/execute.html) | [jvm]<br>abstract fun [execute](../-action/execute.html)() |
| [getContext](../-action/get-context.html) | [jvm]<br>abstract fun [getContext](../-action/get-context.html)(): [Context](../-context/index.html) |
| [getOutboundDependencies](../-action/get-outbound-dependencies.html) | [jvm]<br>abstract fun [getOutboundDependencies](../-action/get-outbound-dependencies.html)(): ListSet<out [Dependency](../-dependency/index.html)> |
| [nextPosition](next-position.html) | [jvm]<br>abstract fun [nextPosition](next-position.html)(): [P](index.html)<br>The position the owner of this action moves to when it is executed, in relative coordinates with respect to its current position. |


## Inheritors


| Name |
|---|
| [AbstractSteeringAction](../../it.unibo.alchemist.model.implementations.actions/-abstract-steering-action/index.html) |
| [GroupSteeringAction](../-group-steering-action/index.html) |
| [NavigationAction](../-navigation-action/index.html) |
| [SteeringActionWithTarget](../-steering-action-with-target/index.html) |

