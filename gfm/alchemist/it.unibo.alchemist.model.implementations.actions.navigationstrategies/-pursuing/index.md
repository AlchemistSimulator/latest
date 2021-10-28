//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.actions.navigationstrategies](../index.md)/[Pursuing](index.md)

# Pursuing

[jvm]\
open class [Pursuing](index.md)<[T](index.md), [L](index.md) : [Euclidean2DConvexShape](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/index.md#-786369621%2FClasslikes%2F-267951372), [R](index.md)>(**action**: [NavigationAction2D](../../it.unibo.alchemist.model.interfaces/index.md#-517309547%2FClasslikes%2F-267951372)<[T](index.md), [L](index.md), [R](index.md), [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.md), [Euclidean2DPassage](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d.graph/-euclidean2-d-passage/index.md)>, **destination**: [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)) : [Exploring](../-exploring/index.md)<[T](index.md), [L](index.md), [R](index.md)> 

A [NavigationStrategy](../../it.unibo.alchemist.model.interfaces/-navigation-strategy/index.md) allowing to pursue a known (static) destination without knowing any path leading there, this is also known as path searching. In this context, knowing a destination means knowing its position, which, in turn, means knowing two things:

<ul><li>the direction that connects the destination and the current position as the crow flies,</li><li>an estimation of the distance between the destination and the current position. In order to reach the destination without a route to follow, the weighting system used in [Exploring](../-exploring/index.md) is extended so as to take into account the (estimated) suitability of each door to reach the provided destination, see suitabilityFactor.</li></ul>

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
| [Pursuing](-pursuing.md) | [jvm]<br>fun [Pursuing](-pursuing.md)(action: [NavigationAction2D](../../it.unibo.alchemist.model.interfaces/index.md#-517309547%2FClasslikes%2F-267951372)<[T](index.md), [L](index.md), [R](index.md), [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.md), [Euclidean2DPassage](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d.graph/-euclidean2-d-passage/index.md)>, destination: [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md))<br>the concentration type. |

## Functions

| Name | Summary |
|---|---|
| [inNewRoom](in-new-room.md) | [jvm]<br>open override fun [inNewRoom](in-new-room.md)(newRoom: [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.md))<br>This is called whenever the pedestrian enters a new room. |
| [inUnexpectedNewRoom](index.md#-1340250552%2FFunctions%2F-267951372) | [jvm]<br>open fun [inUnexpectedNewRoom](index.md#-1340250552%2FFunctions%2F-267951372)(previousRoom: [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.md), expectedNewRoom: [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.md), actualNewRoom: [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.md))<br>This is called in place of [inNewRoom](../../it.unibo.alchemist.model.interfaces/-navigation-strategy/in-new-room.md) when the pedestrian ends up in an unexpected room while moving. |

## Properties

| Name | Summary |
|---|---|
| [action](index.md#-1390831198%2FProperties%2F-267951372) | [jvm]<br>open override val [action](index.md#-1390831198%2FProperties%2F-267951372): [NavigationAction2D](../../it.unibo.alchemist.model.interfaces/index.md#-517309547%2FClasslikes%2F-267951372)<[T](index.md), [L](index.md), [R](index.md), [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.md), [Euclidean2DPassage](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d.graph/-euclidean2-d-passage/index.md)><br>The NavigationAction used to navigate the environment. |

## Inheritors

| Name |
|---|
| [DynamicPursuing](../-dynamic-pursuing/index.md) |
