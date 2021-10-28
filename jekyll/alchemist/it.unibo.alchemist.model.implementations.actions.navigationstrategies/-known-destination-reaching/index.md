---
title: KnownDestinationReaching
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.actions.navigationstrategies](../index.html)/[KnownDestinationReaching](index.html)



# KnownDestinationReaching



[jvm]\
open class [KnownDestinationReaching](index.html)<[T](index.html), [L](index.html) : [Euclidean2DConvexShape](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/index.html#-786369621%2FClasslikes%2F-134779887), [R](index.html)>(**action**: [NavigationAction2D](../../it.unibo.alchemist.model.interfaces/index.html#-517309547%2FClasslikes%2F-134779887)<[T](index.html), [L](index.html), [R](index.html), [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.html), [Euclidean2DPassage](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d.graph/-euclidean2-d-passage/index.html)>, **destinations**: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)>) : [RouteFollowing](../-route-following/index.html)<[T](index.html), [L](index.html), [R](index.html)> 

A [NavigationStrategy](../../it.unibo.alchemist.model.interfaces/-navigation-strategy/index.html) allowing to reach a known (static) destination (see [Pursuing](../-pursuing/index.html)). The client can specify a list of known destinations, the pedestrian will try to reach the closest one for which a valid path leading there is known. The difference between this behavior and [Pursuing](../-pursuing/index.html) is that the latter assumes no route leading to the destination is known, whereas this behavior tries to exploit the pedestrian's cognitive map to obtain a route to follow.



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
| [KnownDestinationReaching](-known-destination-reaching.html) | [jvm]<br>fun [KnownDestinationReaching](-known-destination-reaching.html)(action: [NavigationAction2D](../../it.unibo.alchemist.model.interfaces/index.html#-517309547%2FClasslikes%2F-134779887)<[T](index.html), [L](index.html), [R](index.html), [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.html), [Euclidean2DPassage](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d.graph/-euclidean2-d-passage/index.html)>, destinations: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)>)<br>the concentration type. |


## Functions


| Name | Summary |
|---|---|
| [inNewRoom](../-route-following/in-new-room.html) | [jvm]<br>open override fun [inNewRoom](../-route-following/in-new-room.html)(newRoom: [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.html))<br>This is called whenever the pedestrian enters a new room. |
| [inUnexpectedNewRoom](../-route-following/in-unexpected-new-room.html) | [jvm]<br>open override fun [inUnexpectedNewRoom](../-route-following/in-unexpected-new-room.html)(previousRoom: [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.html), expectedNewRoom: [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.html), actualNewRoom: [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.html))<br>When in an unexpected room the pedestrian gets back to [previousRoom](../-route-following/in-unexpected-new-room.html) so as to continue following the route correctly. |
| [setDestination](../-dynamic-pursuing/set-destination.html) | [jvm]<br>fun [setDestination](../-dynamic-pursuing/set-destination.html)(newDestination: [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html), voidVolatileMemory: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false)<br>Changes the destination of the strategy. |


## Properties


| Name | Summary |
|---|---|
| [action](index.html#2117094345%2FProperties%2F-134779887) | [jvm]<br>open override val [action](index.html#2117094345%2FProperties%2F-134779887): [NavigationAction2D](../../it.unibo.alchemist.model.interfaces/index.html#-517309547%2FClasslikes%2F-134779887)<[T](index.html), [L](index.html), [R](index.html), [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.html), [Euclidean2DPassage](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d.graph/-euclidean2-d-passage/index.html)><br>The NavigationAction used to navigate the environment. |
| [destination](index.html#-2005291219%2FProperties%2F-134779887) | [jvm]<br>protected open override var [destination](index.html#-2005291219%2FProperties%2F-134779887): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)<br>The destination to pursue. |

