---
title: RouteFollowing
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.actions.navigationstrategies](../index.html)/[RouteFollowing](index.html)



# RouteFollowing



[jvm]\
open class [RouteFollowing](index.html)<[T](index.html), [L](index.html) : [Euclidean2DConvexShape](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/index.html#-786369621%2FClasslikes%2F-134779887), [R](index.html)>(**action**: [NavigationAction2D](../../it.unibo.alchemist.model.interfaces/index.html#-517309547%2FClasslikes%2F-134779887)<[T](index.html), [L](index.html), [R](index.html), [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.html), [Euclidean2DPassage](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d.graph/-euclidean2-d-passage/index.html)>, **route**: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)>) : [DynamicPursuing](../-dynamic-pursuing/index.html)<[T](index.html), [L](index.html), [R](index.html)> 

A [NavigationStrategy](../../it.unibo.alchemist.model.interfaces/-navigation-strategy/index.html) allowing to follow a given route. The route consists of a list of positions (= waypoints) that may or may not be in sight of each other (i.e. the path leading from a waypoint to the next one may or may not be representable as a single segment), for this reason [Pursuing](../-pursuing/index.html) behavior is used to reach each waypoint. In this context, a waypoint is considered reached when it's inside the current room (not when the pedestrian reach that exact position), apart from the last waypoint which is actually approached. Cuts to the route are allowed (i.e. if the pedestrian finds a waypoint which is farther than the expected next one, he/she skips all the waypoints in between).



## Parameters


jvm

| | |
|---|---|
| T | the concentration type. |
| L | the type of landmarks of the pedestrian's cognitive map. |
| R | the type of edges of the pedestrian's cognitive map, representing the [R](index.html)elations between landmarks. |



## Constructors


| | |
|---|---|
| [RouteFollowing](-route-following.html) | [jvm]<br>fun [RouteFollowing](-route-following.html)(action: [NavigationAction2D](../../it.unibo.alchemist.model.interfaces/index.html#-517309547%2FClasslikes%2F-134779887)<[T](index.html), [L](index.html), [R](index.html), [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.html), [Euclidean2DPassage](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d.graph/-euclidean2-d-passage/index.html)>, route: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)>)<br>the concentration type. |


## Functions


| Name | Summary |
|---|---|
| [inNewRoom](in-new-room.html) | [jvm]<br>open override fun [inNewRoom](in-new-room.html)(newRoom: [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.html))<br>This is called whenever the pedestrian enters a new room. |
| [inUnexpectedNewRoom](in-unexpected-new-room.html) | [jvm]<br>open override fun [inUnexpectedNewRoom](in-unexpected-new-room.html)(previousRoom: [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.html), expectedNewRoom: [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.html), actualNewRoom: [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.html))<br>When in an unexpected room the pedestrian gets back to [previousRoom](in-unexpected-new-room.html) so as to continue following the route correctly. |
| [setDestination](../-dynamic-pursuing/set-destination.html) | [jvm]<br>fun [setDestination](../-dynamic-pursuing/set-destination.html)(newDestination: [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html), voidVolatileMemory: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false)<br>Changes the destination of the strategy. |


## Properties


| Name | Summary |
|---|---|
| [action](index.html#-1257523369%2FProperties%2F-134779887) | [jvm]<br>open override val [action](index.html#-1257523369%2FProperties%2F-134779887): [NavigationAction2D](../../it.unibo.alchemist.model.interfaces/index.html#-517309547%2FClasslikes%2F-134779887)<[T](index.html), [L](index.html), [R](index.html), [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.html), [Euclidean2DPassage](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d.graph/-euclidean2-d-passage/index.html)><br>The NavigationAction used to navigate the environment. |
| [destination](index.html#-346469281%2FProperties%2F-134779887) | [jvm]<br>protected open override var [destination](index.html#-346469281%2FProperties%2F-134779887): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)<br>The destination to pursue. |


## Inheritors


| Name |
|---|
| [KnownDestinationReaching](../-known-destination-reaching/index.html) |

