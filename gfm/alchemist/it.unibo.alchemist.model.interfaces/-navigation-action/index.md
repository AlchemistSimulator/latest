//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces](../index.md)/[NavigationAction](index.md)

# NavigationAction

[jvm]\
interface [NavigationAction](index.md)<[T](index.md), [P](index.md) : [Position](../-position/index.md)<[P](index.md)>, [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.md)<[P](index.md)>, [A](index.md) : [GeometricTransformation](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-transformation/index.md)<[P](index.md)>, [L](index.md) : [ConvexGeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-convex-geometric-shape/index.md)<[P](index.md), [A](index.md)>, [R](index.md), [N](index.md) : [ConvexGeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-convex-geometric-shape/index.md)<[P](index.md), [A](index.md)>, [E](index.md)> : [SteeringAction](../-steering-action/index.md)<[T](index.md), [P](index.md)> 

A [SteeringAction](../-steering-action/index.md) allowing a pedestrian to navigate an environment consciously (e.g. without getting stuck in U-shaped obstacles). Names are inspired to indoor environments, but this interface works for outdoor ones as well.

## Parameters

jvm

| | |
|---|---|
| T | the concentration type. |
| P | the [Position](../-position/index.md) type and [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.md) type for the space the pedestrian is into. |
| A | the transformations supported by the shapes in this space. |
| L | the type of landmarks of the pedestrian's cognitive map. |
| R | the type of edges of the pedestrian's cognitive map, representing the [R](index.md)elations between landmarks. |
| N | the type of nodes of the navigation graph provided by the [environment](environment.md). |
| E | the type of edges of the navigation graph provided by the [environment](environment.md). |

## Functions

| Name | Summary |
|---|---|
| [cloneAction](../-steering-action-with-target/index.md#1308842947%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [cloneAction](../-steering-action-with-target/index.md#1308842947%2FFunctions%2F-267951372)(p0: [Node](../-node/index.md)<[T](index.md)>, p1: [Reaction](../-reaction/index.md)<[T](index.md)>): [Action](../-action/index.md)<[T](index.md)> |
| [crossDoor](cross-door.md) | [jvm]<br>abstract fun [crossDoor](cross-door.md)(door: [E](index.md))<br>Moves the pedestrian across the provided [door](cross-door.md), which must be among [doorsInSight](doors-in-sight.md). |
| [doorsInSight](doors-in-sight.md) | [jvm]<br>abstract fun [doorsInSight](doors-in-sight.md)(): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[E](index.md)> |
| [execute](../-action/execute.md) | [jvm]<br>abstract fun [execute](../-action/execute.md)() |
| [getContext](../-action/get-context.md) | [jvm]<br>abstract fun [getContext](../-action/get-context.md)(): [Context](../-context/index.md) |
| [getOutboundDependencies](../-action/get-outbound-dependencies.md) | [jvm]<br>abstract fun [getOutboundDependencies](../-action/get-outbound-dependencies.md)(): ListSet<out [Dependency](../-dependency/index.md)> |
| [moveToFinal](move-to-final.md) | [jvm]<br>abstract fun [moveToFinal](move-to-final.md)(destination: [P](index.md))<br>Moves the pedestrian to the given final [destination](move-to-final.md), which must be inside [currentRoom](current-room.md). |
| [nextPosition](../-steering-action/next-position.md) | [jvm]<br>abstract fun [nextPosition](../-steering-action/next-position.md)(): [P](index.md)<br>The position the owner of this action moves to when it is executed, in relative coordinates with respect to its current position. |
| [stop](stop.md) | [jvm]<br>open fun [stop](stop.md)()<br>Stops moving the pedestrian. |

## Properties

| Name | Summary |
|---|---|
| [currentRoom](current-room.md) | [jvm]<br>abstract val [currentRoom](current-room.md): [N](index.md)?<br>The room (= environment's area) the [pedestrian](pedestrian.md) is into. |
| [environment](environment.md) | [jvm]<br>abstract val [environment](environment.md): [EnvironmentWithGraph](../../it.unibo.alchemist.model.interfaces.environments/-environment-with-graph/index.md)<*, [T](index.md), [P](index.md), [A](index.md), [N](index.md), [E](index.md)><br>The environment the [pedestrian](pedestrian.md) is into. |
| [pedestrian](pedestrian.md) | [jvm]<br>abstract val [pedestrian](pedestrian.md): [OrientingPedestrian](../-orienting-pedestrian/index.md)<[T](index.md), [P](index.md), [A](index.md), [L](index.md), [R](index.md)><br>The pedestrian to move. |
| [pedestrianPosition](pedestrian-position.md) | [jvm]<br>abstract val [pedestrianPosition](pedestrian-position.md): [P](index.md)<br>The position of the [pedestrian](pedestrian.md) in the [environment](environment.md). |

## Inheritors

| Name |
|---|
| [AbstractNavigationAction](../../it.unibo.alchemist.model.implementations.actions/-abstract-navigation-action/index.md) |
