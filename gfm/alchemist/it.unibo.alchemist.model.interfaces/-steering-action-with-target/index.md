//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces](../index.md)/[SteeringActionWithTarget](index.md)

# SteeringActionWithTarget

[jvm]\
interface [SteeringActionWithTarget](index.md)<[T](index.md), [P](index.md) : [Position](../-position/index.md)<[P](index.md)>, [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.md)<[P](index.md)>> : [SteeringAction](../-steering-action/index.md)<[T](index.md), [P](index.md)> 

A [SteeringAction](../-steering-action/index.md) with a defined target.

## Functions

| Name | Summary |
|---|---|
| [cloneAction](index.md#1308842947%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [cloneAction](index.md#1308842947%2FFunctions%2F-267951372)(p0: [Node](../-node/index.md)<[T](index.md)>, p1: [Reaction](../-reaction/index.md)<[T](index.md)>): [Action](../-action/index.md)<[T](index.md)> |
| [execute](../-action/execute.md) | [jvm]<br>abstract fun [execute](../-action/execute.md)() |
| [getContext](../-action/get-context.md) | [jvm]<br>abstract fun [getContext](../-action/get-context.md)(): [Context](../-context/index.md) |
| [getOutboundDependencies](../-action/get-outbound-dependencies.md) | [jvm]<br>abstract fun [getOutboundDependencies](../-action/get-outbound-dependencies.md)(): ListSet<out [Dependency](../-dependency/index.md)> |
| [nextPosition](../-steering-action/next-position.md) | [jvm]<br>abstract fun [nextPosition](../-steering-action/next-position.md)(): [P](index.md)<br>The position the owner of this action moves to when it is executed, in relative coordinates with respect to its current position. |
| [target](target.md) | [jvm]<br>abstract fun [target](target.md)(): [P](index.md)<br>The position the owner of this action moves towards, in absolute coordinates. |

## Inheritors

| Name |
|---|
| [AbstractSteeringActionWithTarget](../../it.unibo.alchemist.model.implementations.actions/-abstract-steering-action-with-target/index.md) |
| [CognitiveAgentSeek2D](../../it.unibo.alchemist.model.implementations.actions/-cognitive-agent-seek2-d/index.md) |

## Extensions

| Name | Summary |
|---|---|
| [targetDistanceTo](../../it.unibo.alchemist.model.implementations.actions.steeringstrategies/target-distance-to.md) | [jvm]<br>fun <[T](../../it.unibo.alchemist.model.implementations.actions.steeringstrategies/target-distance-to.md), [P](../../it.unibo.alchemist.model.implementations.actions.steeringstrategies/target-distance-to.md) : [Position](../-position/index.md)<[P](../../it.unibo.alchemist.model.implementations.actions.steeringstrategies/target-distance-to.md)>, [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.md)<[P](../../it.unibo.alchemist.model.implementations.actions.steeringstrategies/target-distance-to.md)>> [SteeringActionWithTarget](index.md)<[T](../../it.unibo.alchemist.model.implementations.actions.steeringstrategies/target-distance-to.md), [P](../../it.unibo.alchemist.model.implementations.actions.steeringstrategies/target-distance-to.md)>.[targetDistanceTo](../../it.unibo.alchemist.model.implementations.actions.steeringstrategies/target-distance-to.md)(node: [Node](../-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.actions.steeringstrategies/target-distance-to.md)>, env: [Environment](../-environment/index.md)<[T](../../it.unibo.alchemist.model.implementations.actions.steeringstrategies/target-distance-to.md), [P](../../it.unibo.alchemist.model.implementations.actions.steeringstrategies/target-distance-to.md)>): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Computes the distance between this action's target and the given [node](../../it.unibo.alchemist.model.implementations.actions.steeringstrategies/target-distance-to.md). |
