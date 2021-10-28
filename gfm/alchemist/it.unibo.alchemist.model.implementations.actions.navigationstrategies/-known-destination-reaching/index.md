//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.actions.navigationstrategies](../index.md)/[KnownDestinationReaching](index.md)

# KnownDestinationReaching

[jvm]\
open class [KnownDestinationReaching](index.md)<[T](index.md), [L](index.md) : [Euclidean2DConvexShape](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/index.md#-786369621%2FClasslikes%2F-267951372), [R](index.md)>(**action**: [NavigationAction2D](../../it.unibo.alchemist.model.interfaces/index.md#-517309547%2FClasslikes%2F-267951372)<[T](index.md), [L](index.md), [R](index.md), [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.md), [Euclidean2DPassage](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d.graph/-euclidean2-d-passage/index.md)>, **destinations**: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)>) : [RouteFollowing](../-route-following/index.md)<[T](index.md), [L](index.md), [R](index.md)> 

A [NavigationStrategy](../../it.unibo.alchemist.model.interfaces/-navigation-strategy/index.md) allowing to reach a known (static) destination (see [Pursuing](../-pursuing/index.md)). The client can specify a list of known destinations, the pedestrian will try to reach the closest one for which a valid path leading there is known. The difference between this behavior and [Pursuing](../-pursuing/index.md) is that the latter assumes no route leading to the destination is known, whereas this behavior tries to exploit the pedestrian's cognitive map to obtain a route to follow.

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
| [KnownDestinationReaching](-known-destination-reaching.md) | [jvm]<br>fun [KnownDestinationReaching](-known-destination-reaching.md)(action: [NavigationAction2D](../../it.unibo.alchemist.model.interfaces/index.md#-517309547%2FClasslikes%2F-267951372)<[T](index.md), [L](index.md), [R](index.md), [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.md), [Euclidean2DPassage](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d.graph/-euclidean2-d-passage/index.md)>, destinations: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)>)<br>the concentration type. |

## Functions

| Name | Summary |
|---|---|
| [inNewRoom](../-route-following/in-new-room.md) | [jvm]<br>open override fun [inNewRoom](../-route-following/in-new-room.md)(newRoom: [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.md))<br>This is called whenever the pedestrian enters a new room. |
| [inUnexpectedNewRoom](../-route-following/in-unexpected-new-room.md) | [jvm]<br>open override fun [inUnexpectedNewRoom](../-route-following/in-unexpected-new-room.md)(previousRoom: [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.md), expectedNewRoom: [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.md), actualNewRoom: [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.md))<br>When in an unexpected room the pedestrian gets back to [previousRoom](../-route-following/in-unexpected-new-room.md) so as to continue following the route correctly. |
| [setDestination](../-dynamic-pursuing/set-destination.md) | [jvm]<br>fun [setDestination](../-dynamic-pursuing/set-destination.md)(newDestination: [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md), voidVolatileMemory: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false)<br>Changes the destination of the strategy. |

## Properties

| Name | Summary |
|---|---|
| [action](index.md#2117094345%2FProperties%2F-267951372) | [jvm]<br>open override val [action](index.md#2117094345%2FProperties%2F-267951372): [NavigationAction2D](../../it.unibo.alchemist.model.interfaces/index.md#-517309547%2FClasslikes%2F-267951372)<[T](index.md), [L](index.md), [R](index.md), [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.md), [Euclidean2DPassage](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d.graph/-euclidean2-d-passage/index.md)><br>The NavigationAction used to navigate the environment. |
| [destination](index.md#-2005291219%2FProperties%2F-267951372) | [jvm]<br>protected open override var [destination](index.md#-2005291219%2FProperties%2F-267951372): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)<br>The destination to pursue. |
