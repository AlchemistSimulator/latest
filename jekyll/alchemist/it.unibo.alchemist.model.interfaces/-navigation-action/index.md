---
title: NavigationAction
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces](../index.html)/[NavigationAction](index.html)



# NavigationAction



[jvm]\
interface [NavigationAction](index.html)<[T](index.html), [P](index.html) : [Position](../-position/index.html)<[P](index.html)>, [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html)<[P](index.html)>, [A](index.html) : [GeometricTransformation](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-transformation/index.html)<[P](index.html)>, [L](index.html) : [ConvexGeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-convex-geometric-shape/index.html)<[P](index.html), [A](index.html)>, [R](index.html), [N](index.html) : [ConvexGeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-convex-geometric-shape/index.html)<[P](index.html), [A](index.html)>, [E](index.html)> : [SteeringAction](../-steering-action/index.html)<[T](index.html), [P](index.html)> 

A [SteeringAction](../-steering-action/index.html) allowing a pedestrian to navigate an environment consciously (e.g. without getting stuck in U-shaped obstacles). Names are inspired to indoor environments, but this interface works for outdoor ones as well.



## Parameters


jvm

| | |
|---|---|
| T | the concentration type. |
| P | the [Position](../-position/index.html) type and [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html) type for the space the pedestrian is into. |
| A | the transformations supported by the shapes in this space. |
| L | the type of landmarks of the pedestrian's cognitive map. |
| R | the type of edges of the pedestrian's cognitive map, representing the [R](index.html)elations between landmarks. |
| N | the type of nodes of the navigation graph provided by the [environment](environment.html). |
| E | the type of edges of the navigation graph provided by the [environment](environment.html). |



## Functions


| Name | Summary |
|---|---|
| [cloneAction](../-steering-action-with-target/index.html#1308842947%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [cloneAction](../-steering-action-with-target/index.html#1308842947%2FFunctions%2F-134779887)(p0: [Node](../-node/index.html)<[T](index.html)>, p1: [Reaction](../-reaction/index.html)<[T](index.html)>): [Action](../-action/index.html)<[T](index.html)> |
| [crossDoor](cross-door.html) | [jvm]<br>abstract fun [crossDoor](cross-door.html)(door: [E](index.html))<br>Moves the pedestrian across the provided [door](cross-door.html), which must be among [doorsInSight](doors-in-sight.html). |
| [doorsInSight](doors-in-sight.html) | [jvm]<br>abstract fun [doorsInSight](doors-in-sight.html)(): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[E](index.html)> |
| [execute](../-action/execute.html) | [jvm]<br>abstract fun [execute](../-action/execute.html)() |
| [getContext](../-action/get-context.html) | [jvm]<br>abstract fun [getContext](../-action/get-context.html)(): [Context](../-context/index.html) |
| [getOutboundDependencies](../-action/get-outbound-dependencies.html) | [jvm]<br>abstract fun [getOutboundDependencies](../-action/get-outbound-dependencies.html)(): ListSet<out [Dependency](../-dependency/index.html)> |
| [moveToFinal](move-to-final.html) | [jvm]<br>abstract fun [moveToFinal](move-to-final.html)(destination: [P](index.html))<br>Moves the pedestrian to the given final [destination](move-to-final.html), which must be inside [currentRoom](current-room.html). |
| [nextPosition](../-steering-action/next-position.html) | [jvm]<br>abstract fun [nextPosition](../-steering-action/next-position.html)(): [P](index.html)<br>The position the owner of this action moves to when it is executed, in relative coordinates with respect to its current position. |
| [stop](stop.html) | [jvm]<br>open fun [stop](stop.html)()<br>Stops moving the pedestrian. |


## Properties


| Name | Summary |
|---|---|
| [currentRoom](current-room.html) | [jvm]<br>abstract val [currentRoom](current-room.html): [N](index.html)?<br>The room (= environment's area) the [pedestrian](pedestrian.html) is into. |
| [environment](environment.html) | [jvm]<br>abstract val [environment](environment.html): [EnvironmentWithGraph](../../it.unibo.alchemist.model.interfaces.environments/-environment-with-graph/index.html)<*, [T](index.html), [P](index.html), [A](index.html), [N](index.html), [E](index.html)><br>The environment the [pedestrian](pedestrian.html) is into. |
| [pedestrian](pedestrian.html) | [jvm]<br>abstract val [pedestrian](pedestrian.html): [OrientingPedestrian](../-orienting-pedestrian/index.html)<[T](index.html), [P](index.html), [A](index.html), [L](index.html), [R](index.html)><br>The pedestrian to move. |
| [pedestrianPosition](pedestrian-position.html) | [jvm]<br>abstract val [pedestrianPosition](pedestrian-position.html): [P](index.html)<br>The position of the [pedestrian](pedestrian.html) in the [environment](environment.html). |


## Inheritors


| Name |
|---|
| [AbstractNavigationAction](../../it.unibo.alchemist.model.implementations.actions/-abstract-navigation-action/index.html) |

