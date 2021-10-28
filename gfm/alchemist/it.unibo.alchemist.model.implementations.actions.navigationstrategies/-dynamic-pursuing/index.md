//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.actions.navigationstrategies](../index.md)/[DynamicPursuing](index.md)

# DynamicPursuing

[jvm]\
open class [DynamicPursuing](index.md)<[T](index.md), [L](index.md) : [Euclidean2DConvexShape](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/index.md#-786369621%2FClasslikes%2F-267951372), [R](index.md)>(**action**: [NavigationAction2D](../../it.unibo.alchemist.model.interfaces/index.md#-517309547%2FClasslikes%2F-267951372)<[T](index.md), [L](index.md), [R](index.md), [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.md), [Euclidean2DPassage](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d.graph/-euclidean2-d-passage/index.md)>, **destination**: [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)) : [Pursuing](../-pursuing/index.md)<[T](index.md), [L](index.md), [R](index.md)> 

[Pursuing](../-pursuing/index.md) strategy allowing to dynamically change [destination](destination.md).

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
| [DynamicPursuing](-dynamic-pursuing.md) | [jvm]<br>fun [DynamicPursuing](-dynamic-pursuing.md)(action: [NavigationAction2D](../../it.unibo.alchemist.model.interfaces/index.md#-517309547%2FClasslikes%2F-267951372)<[T](index.md), [L](index.md), [R](index.md), [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.md), [Euclidean2DPassage](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d.graph/-euclidean2-d-passage/index.md)>, destination: [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md))<br>the concentration type. |

## Functions

| Name | Summary |
|---|---|
| [inNewRoom](../-pursuing/in-new-room.md) | [jvm]<br>open override fun [inNewRoom](../-pursuing/in-new-room.md)(newRoom: [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.md))<br>This is called whenever the pedestrian enters a new room. |
| [inUnexpectedNewRoom](../-pursuing/index.md#-1340250552%2FFunctions%2F-267951372) | [jvm]<br>open fun [inUnexpectedNewRoom](../-pursuing/index.md#-1340250552%2FFunctions%2F-267951372)(previousRoom: [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.md), expectedNewRoom: [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.md), actualNewRoom: [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.md))<br>This is called in place of [inNewRoom](../../it.unibo.alchemist.model.interfaces/-navigation-strategy/in-new-room.md) when the pedestrian ends up in an unexpected room while moving. |
| [setDestination](set-destination.md) | [jvm]<br>fun [setDestination](set-destination.md)(newDestination: [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md), voidVolatileMemory: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false)<br>Changes the destination of the strategy. |

## Properties

| Name | Summary |
|---|---|
| [action](index.md#-2063776013%2FProperties%2F-267951372) | [jvm]<br>open override val [action](index.md#-2063776013%2FProperties%2F-267951372): [NavigationAction2D](../../it.unibo.alchemist.model.interfaces/index.md#-517309547%2FClasslikes%2F-267951372)<[T](index.md), [L](index.md), [R](index.md), [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.md), [Euclidean2DPassage](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d.graph/-euclidean2-d-passage/index.md)><br>The NavigationAction used to navigate the environment. |
| [destination](destination.md) | [jvm]<br>protected open override var [destination](destination.md): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)<br>The destination to pursue. |

## Inheritors

| Name |
|---|
| [RouteFollowing](../-route-following/index.md) |
