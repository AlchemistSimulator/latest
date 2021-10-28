//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces](../index.md)/[GroupSteeringAction](index.md)

# GroupSteeringAction

[jvm]\
interface [GroupSteeringAction](index.md)<[T](index.md), [P](index.md) : [Position](../-position/index.md)<[P](index.md)>, [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.md)<[P](index.md)>> : [SteeringAction](../-steering-action/index.md)<[T](index.md), [P](index.md)> 

A [SteeringAction](../-steering-action/index.md) related to a group of pedestrians.

## Functions

| Name | Summary |
|---|---|
| [cloneAction](../-steering-action-with-target/index.md#1308842947%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [cloneAction](../-steering-action-with-target/index.md#1308842947%2FFunctions%2F-267951372)(p0: [Node](../-node/index.md)<[T](index.md)>, p1: [Reaction](../-reaction/index.md)<[T](index.md)>): [Action](../-action/index.md)<[T](index.md)> |
| [execute](../-action/execute.md) | [jvm]<br>abstract fun [execute](../-action/execute.md)() |
| [getContext](../-action/get-context.md) | [jvm]<br>abstract fun [getContext](../-action/get-context.md)(): [Context](../-context/index.md) |
| [getOutboundDependencies](../-action/get-outbound-dependencies.md) | [jvm]<br>abstract fun [getOutboundDependencies](../-action/get-outbound-dependencies.md)(): ListSet<out [Dependency](../-dependency/index.md)> |
| [group](group.md) | [jvm]<br>abstract fun [group](group.md)(): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Pedestrian](../-pedestrian/index.md)<[T](index.md), [P](index.md), *>><br>The list of pedestrians influencing this action. |
| [nextPosition](../-steering-action/next-position.md) | [jvm]<br>abstract fun [nextPosition](../-steering-action/next-position.md)(): [P](index.md)<br>The position the owner of this action moves to when it is executed, in relative coordinates with respect to its current position. |

## Inheritors

| Name |
|---|
| [AbstractGroupSteeringAction](../../it.unibo.alchemist.model.implementations.actions/-abstract-group-steering-action/index.md) |
