---
title: Pursuing
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.actions.navigationstrategies](../index.html)/[Pursuing](index.html)



# Pursuing



[jvm]\
open class [Pursuing](index.html)<[T](index.html), [L](index.html) : [Euclidean2DConvexShape](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/index.html#-786369621%2FClasslikes%2F-134779887), [R](index.html)>(**action**: [NavigationAction2D](../../it.unibo.alchemist.model.interfaces/index.html#-517309547%2FClasslikes%2F-134779887)<[T](index.html), [L](index.html), [R](index.html), [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.html), [Euclidean2DPassage](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d.graph/-euclidean2-d-passage/index.html)>, **destination**: [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)) : [Exploring](../-exploring/index.html)<[T](index.html), [L](index.html), [R](index.html)> 

A [NavigationStrategy](../../it.unibo.alchemist.model.interfaces/-navigation-strategy/index.html) allowing to pursue a known (static) destination without knowing any path leading there, this is also known as path searching. In this context, knowing a destination means knowing its position, which, in turn, means knowing two things:



<ul><li>the direction that connects the destination and the current position as the crow flies,</li><li>an estimation of the distance between the destination and the current position. In order to reach the destination without a route to follow, the weighting system used in [Exploring](../-exploring/index.html) is extended so as to take into account the (estimated) suitability of each door to reach the provided destination, see suitabilityFactor.</li></ul>



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
| [Pursuing](-pursuing.html) | [jvm]<br>fun [Pursuing](-pursuing.html)(action: [NavigationAction2D](../../it.unibo.alchemist.model.interfaces/index.html#-517309547%2FClasslikes%2F-134779887)<[T](index.html), [L](index.html), [R](index.html), [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.html), [Euclidean2DPassage](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d.graph/-euclidean2-d-passage/index.html)>, destination: [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html))<br>the concentration type. |


## Functions


| Name | Summary |
|---|---|
| [inNewRoom](in-new-room.html) | [jvm]<br>open override fun [inNewRoom](in-new-room.html)(newRoom: [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.html))<br>This is called whenever the pedestrian enters a new room. |
| [inUnexpectedNewRoom](index.html#-1340250552%2FFunctions%2F-134779887) | [jvm]<br>open fun [inUnexpectedNewRoom](index.html#-1340250552%2FFunctions%2F-134779887)(previousRoom: [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.html), expectedNewRoom: [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.html), actualNewRoom: [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.html))<br>This is called in place of [inNewRoom](../../it.unibo.alchemist.model.interfaces/-navigation-strategy/in-new-room.html) when the pedestrian ends up in an unexpected room while moving. |


## Properties


| Name | Summary |
|---|---|
| [action](index.html#-1390831198%2FProperties%2F-134779887) | [jvm]<br>open override val [action](index.html#-1390831198%2FProperties%2F-134779887): [NavigationAction2D](../../it.unibo.alchemist.model.interfaces/index.html#-517309547%2FClasslikes%2F-134779887)<[T](index.html), [L](index.html), [R](index.html), [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.html), [Euclidean2DPassage](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d.graph/-euclidean2-d-passage/index.html)><br>The NavigationAction used to navigate the environment. |


## Inheritors


| Name |
|---|
| [DynamicPursuing](../-dynamic-pursuing/index.html) |

