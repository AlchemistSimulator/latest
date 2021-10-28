//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.actions.navigationstrategies](../index.md)/[RouteFollowing](index.md)

# RouteFollowing

[jvm]\
open class [RouteFollowing](index.md)<[T](index.md), [L](index.md) : [Euclidean2DConvexShape](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/index.md#-786369621%2FClasslikes%2F-267951372), [R](index.md)>(**action**: [NavigationAction2D](../../it.unibo.alchemist.model.interfaces/index.md#-517309547%2FClasslikes%2F-267951372)<[T](index.md), [L](index.md), [R](index.md), [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.md), [Euclidean2DPassage](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d.graph/-euclidean2-d-passage/index.md)>, **route**: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)>) : [DynamicPursuing](../-dynamic-pursuing/index.md)<[T](index.md), [L](index.md), [R](index.md)> 

A [NavigationStrategy](../../it.unibo.alchemist.model.interfaces/-navigation-strategy/index.md) allowing to follow a given route. The route consists of a list of positions (= waypoints) that may or may not be in sight of each other (i.e. the path leading from a waypoint to the next one may or may not be representable as a single segment), for this reason [Pursuing](../-pursuing/index.md) behavior is used to reach each waypoint. In this context, a waypoint is considered reached when it's inside the current room (not when the pedestrian reach that exact position), apart from the last waypoint which is actually approached. Cuts to the route are allowed (i.e. if the pedestrian finds a waypoint which is farther than the expected next one, he/she skips all the waypoints in between).

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
| [RouteFollowing](-route-following.md) | [jvm]<br>fun [RouteFollowing](-route-following.md)(action: [NavigationAction2D](../../it.unibo.alchemist.model.interfaces/index.md#-517309547%2FClasslikes%2F-267951372)<[T](index.md), [L](index.md), [R](index.md), [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.md), [Euclidean2DPassage](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d.graph/-euclidean2-d-passage/index.md)>, route: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)>)<br>the concentration type. |

## Functions

| Name | Summary |
|---|---|
| [inNewRoom](in-new-room.md) | [jvm]<br>open override fun [inNewRoom](in-new-room.md)(newRoom: [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.md))<br>This is called whenever the pedestrian enters a new room. |
| [inUnexpectedNewRoom](in-unexpected-new-room.md) | [jvm]<br>open override fun [inUnexpectedNewRoom](in-unexpected-new-room.md)(previousRoom: [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.md), expectedNewRoom: [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.md), actualNewRoom: [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.md))<br>When in an unexpected room the pedestrian gets back to [previousRoom](in-unexpected-new-room.md) so as to continue following the route correctly. |
| [setDestination](../-dynamic-pursuing/set-destination.md) | [jvm]<br>fun [setDestination](../-dynamic-pursuing/set-destination.md)(newDestination: [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md), voidVolatileMemory: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false)<br>Changes the destination of the strategy. |

## Properties

| Name | Summary |
|---|---|
| [action](index.md#-1257523369%2FProperties%2F-267951372) | [jvm]<br>open override val [action](index.md#-1257523369%2FProperties%2F-267951372): [NavigationAction2D](../../it.unibo.alchemist.model.interfaces/index.md#-517309547%2FClasslikes%2F-267951372)<[T](index.md), [L](index.md), [R](index.md), [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.md), [Euclidean2DPassage](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d.graph/-euclidean2-d-passage/index.md)><br>The NavigationAction used to navigate the environment. |
| [destination](index.md#-346469281%2FProperties%2F-267951372) | [jvm]<br>protected open override var [destination](index.md#-346469281%2FProperties%2F-267951372): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)<br>The destination to pursue. |

## Inheritors

| Name |
|---|
| [KnownDestinationReaching](../-known-destination-reaching/index.md) |
