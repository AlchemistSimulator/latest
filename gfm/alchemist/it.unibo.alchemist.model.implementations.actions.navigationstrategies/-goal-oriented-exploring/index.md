//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.actions.navigationstrategies](../index.md)/[GoalOrientedExploring](index.md)

# GoalOrientedExploring

[jvm]\
open class [GoalOrientedExploring](index.md)<[T](index.md), [L](index.md) : [Euclidean2DConvexShape](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/index.md#-786369621%2FClasslikes%2F-267951372), [R](index.md)>(**action**: [NavigationAction2D](../../it.unibo.alchemist.model.interfaces/index.md#-517309547%2FClasslikes%2F-267951372)<[T](index.md), [L](index.md), [R](index.md), [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.md), [Euclidean2DPassage](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d.graph/-euclidean2-d-passage/index.md)>, **unknownDestinations**: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)>) : [Exploring](../-exploring/index.md)<[T](index.md), [L](index.md), [R](index.md)> 

A [NavigationStrategy](../../it.unibo.alchemist.model.interfaces/-navigation-strategy/index.md) allowing to explore the environment looking for something specific whose position is unknown. The client can specify a list of unknownDestinations: these can be recognized once they're in sight, but the pedestrian doesn't know their position until that moment (think e.g. of exits in an evacuation scenario). More specifically, unknown destinations can be detected if located in a room adjacent to the room the pedestrian is into. Once a destination is detected, the pedestrian will reach it and stop.

## Parameters

jvm

| | |
|---|---|
| T | the concentration type. |
| L | the type of landmarks of the pedestrian's cognitive map. |
| R | the type of edges of the pedestrian's cognitive map, representing the [R](index.md)elations between landmarks. |

## Constructors

| | |
|---|---|
| [GoalOrientedExploring](-goal-oriented-exploring.md) | [jvm]<br>fun [GoalOrientedExploring](-goal-oriented-exploring.md)(action: [NavigationAction2D](../../it.unibo.alchemist.model.interfaces/index.md#-517309547%2FClasslikes%2F-267951372)<[T](index.md), [L](index.md), [R](index.md), [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.md), [Euclidean2DPassage](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d.graph/-euclidean2-d-passage/index.md)>, unknownDestinations: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)>)<br>the concentration type. |

## Functions

| Name | Summary |
|---|---|
| [inNewRoom](in-new-room.md) | [jvm]<br>open override fun [inNewRoom](in-new-room.md)(newRoom: [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.md))<br>This is called whenever the pedestrian enters a new room. |
| [inUnexpectedNewRoom](../-pursuing/index.md#-1340250552%2FFunctions%2F-267951372) | [jvm]<br>open fun [inUnexpectedNewRoom](../-pursuing/index.md#-1340250552%2FFunctions%2F-267951372)(previousRoom: [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.md), expectedNewRoom: [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.md), actualNewRoom: [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.md))<br>This is called in place of [inNewRoom](../../it.unibo.alchemist.model.interfaces/-navigation-strategy/in-new-room.md) when the pedestrian ends up in an unexpected room while moving. |

## Properties

| Name | Summary |
|---|---|
| [action](index.md#607080442%2FProperties%2F-267951372) | [jvm]<br>open override val [action](index.md#607080442%2FProperties%2F-267951372): [NavigationAction2D](../../it.unibo.alchemist.model.interfaces/index.md#-517309547%2FClasslikes%2F-267951372)<[T](index.md), [L](index.md), [R](index.md), [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.md), [Euclidean2DPassage](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d.graph/-euclidean2-d-passage/index.md)><br>The NavigationAction used to navigate the environment. |

## Inheritors

| Name |
|---|
| [DestinationReaching](../-destination-reaching/index.md) |
