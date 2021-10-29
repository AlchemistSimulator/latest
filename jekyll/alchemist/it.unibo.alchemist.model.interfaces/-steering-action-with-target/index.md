---
title: SteeringActionWithTarget
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces](../index.html)/[SteeringActionWithTarget](index.html)



# SteeringActionWithTarget



[jvm]\
interface [SteeringActionWithTarget](index.html)<[T](index.html), [P](index.html) : [Position](../-position/index.html)<[P](index.html)>, [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html)<[P](index.html)>> : [SteeringAction](../-steering-action/index.html)<[T](index.html), [P](index.html)> 

A [SteeringAction](../-steering-action/index.html) with a defined target.



## Functions


| Name | Summary |
|---|---|
| [cloneAction](index.html#1308842947%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [cloneAction](index.html#1308842947%2FFunctions%2F-134779887)(p0: [Node](../-node/index.html)<[T](index.html)>, p1: [Reaction](../-reaction/index.html)<[T](index.html)>): [Action](../-action/index.html)<[T](index.html)> |
| [execute](../-action/execute.html) | [jvm]<br>abstract fun [execute](../-action/execute.html)() |
| [getContext](../-action/get-context.html) | [jvm]<br>abstract fun [getContext](../-action/get-context.html)(): [Context](../-context/index.html) |
| [getOutboundDependencies](../-action/get-outbound-dependencies.html) | [jvm]<br>abstract fun [getOutboundDependencies](../-action/get-outbound-dependencies.html)(): ListSet<out [Dependency](../-dependency/index.html)> |
| [nextPosition](../-steering-action/next-position.html) | [jvm]<br>abstract fun [nextPosition](../-steering-action/next-position.html)(): [P](index.html)<br>The position the owner of this action moves to when it is executed, in relative coordinates with respect to its current position. |
| [target](target.html) | [jvm]<br>abstract fun [target](target.html)(): [P](index.html)<br>The position the owner of this action moves towards, in absolute coordinates. |


## Inheritors


| Name |
|---|
| [AbstractSteeringActionWithTarget](../../it.unibo.alchemist.model.implementations.actions/-abstract-steering-action-with-target/index.html) |
| [CognitiveAgentSeek2D](../../it.unibo.alchemist.model.implementations.actions/-cognitive-agent-seek2-d/index.html) |


## Extensions


| Name | Summary |
|---|---|
| [targetDistanceTo](../../it.unibo.alchemist.model.implementations.actions.steeringstrategies/target-distance-to.html) | [jvm]<br>fun <[T](../../it.unibo.alchemist.model.implementations.actions.steeringstrategies/target-distance-to.html), [P](../../it.unibo.alchemist.model.implementations.actions.steeringstrategies/target-distance-to.html) : [Position](../-position/index.html)<[P](../../it.unibo.alchemist.model.implementations.actions.steeringstrategies/target-distance-to.html)>, [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html)<[P](../../it.unibo.alchemist.model.implementations.actions.steeringstrategies/target-distance-to.html)>> [SteeringActionWithTarget](index.html)<[T](../../it.unibo.alchemist.model.implementations.actions.steeringstrategies/target-distance-to.html), [P](../../it.unibo.alchemist.model.implementations.actions.steeringstrategies/target-distance-to.html)>.[targetDistanceTo](../../it.unibo.alchemist.model.implementations.actions.steeringstrategies/target-distance-to.html)(node: [Node](../-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.actions.steeringstrategies/target-distance-to.html)>, env: [Environment](../-environment/index.html)<[T](../../it.unibo.alchemist.model.implementations.actions.steeringstrategies/target-distance-to.html), [P](../../it.unibo.alchemist.model.implementations.actions.steeringstrategies/target-distance-to.html)>): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Computes the distance between this action's target and the given [node](../../it.unibo.alchemist.model.implementations.actions.steeringstrategies/target-distance-to.html). |

