//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces](../index.md)/[SteeringAction](index.md)

# SteeringAction

[jvm]\
interface [SteeringAction](index.md)<[T](index.md), [P](index.md) : [Position](../-position/index.md)<[P](index.md)>> : [Action](../-action/index.md)<[T](index.md)> 

Action whose purpose is moving a node inside the environment it is in.

## Functions

| Name | Summary |
|---|---|
| [cloneAction](../-steering-action-with-target/index.md#1308842947%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [cloneAction](../-steering-action-with-target/index.md#1308842947%2FFunctions%2F-267951372)(p0: [Node](../-node/index.md)<[T](index.md)>, p1: [Reaction](../-reaction/index.md)<[T](index.md)>): [Action](../-action/index.md)<[T](index.md)> |
| [execute](../-action/execute.md) | [jvm]<br>abstract fun [execute](../-action/execute.md)() |
| [getContext](../-action/get-context.md) | [jvm]<br>abstract fun [getContext](../-action/get-context.md)(): [Context](../-context/index.md) |
| [getOutboundDependencies](../-action/get-outbound-dependencies.md) | [jvm]<br>abstract fun [getOutboundDependencies](../-action/get-outbound-dependencies.md)(): ListSet<out [Dependency](../-dependency/index.md)> |
| [nextPosition](next-position.md) | [jvm]<br>abstract fun [nextPosition](next-position.md)(): [P](index.md)<br>The position the owner of this action moves to when it is executed, in relative coordinates with respect to its current position. |

## Inheritors

| Name |
|---|
| [AbstractSteeringAction](../../it.unibo.alchemist.model.implementations.actions/-abstract-steering-action/index.md) |
| [GroupSteeringAction](../-group-steering-action/index.md) |
| [NavigationAction](../-navigation-action/index.md) |
| [SteeringActionWithTarget](../-steering-action-with-target/index.md) |
