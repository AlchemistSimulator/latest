---
title: Exploring
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.actions.navigationstrategies](../index.html)/[Exploring](index.html)



# Exploring



[jvm]\
open class [Exploring](index.html)<[T](index.html), [L](index.html) : [Euclidean2DConvexShape](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/index.html#-786369621%2FClasslikes%2F-134779887), [R](index.html)>(**action**: [NavigationAction2D](../../it.unibo.alchemist.model.interfaces/index.html#-517309547%2FClasslikes%2F-134779887)<[T](index.html), [L](index.html), [R](index.html), [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.html), [Euclidean2DPassage](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d.graph/-euclidean2-d-passage/index.html)>, **knownImpasseWeight**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) : [NavigationStrategy](../../it.unibo.alchemist.model.interfaces/-navigation-strategy/index.html)<[T](index.html), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html), [Euclidean2DTransformation](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-euclidean2-d-transformation/index.html), [L](index.html), [R](index.html), [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.html), [Euclidean2DPassage](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d.graph/-euclidean2-d-passage/index.html)> 

A [NavigationStrategy](../../it.unibo.alchemist.model.interfaces/-navigation-strategy/index.html) allowing to explore the environment. In order to choose which direction to take, a weighting system is used: every time the pedestrian enters a new room all the visible doors are weighted, the one with minimum weight is then crossed. The weighting system used here is derived from the one by [Andresen et al.](https://doi.org/10.1080/23249935.2018.1432717), see weight.



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
| [Exploring](-exploring.html) | [jvm]<br>fun [Exploring](-exploring.html)(action: [NavigationAction2D](../../it.unibo.alchemist.model.interfaces/index.html#-517309547%2FClasslikes%2F-134779887)<[T](index.html), [L](index.html), [R](index.html), [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.html), [Euclidean2DPassage](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d.graph/-euclidean2-d-passage/index.html)>, knownImpasseWeight: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = DEFAULT_IMPASSE_WEIGHT)<br>the concentration type. |


## Types


| Name | Summary |
|---|---|
| [Companion](-companion/index.html) | [jvm]<br>object [Companion](-companion/index.html) |


## Functions


| Name | Summary |
|---|---|
| [inNewRoom](in-new-room.html) | [jvm]<br>open override fun [inNewRoom](in-new-room.html)(newRoom: [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.html))<br>This is called whenever the pedestrian enters a new room. |
| [inUnexpectedNewRoom](../-pursuing/index.html#-1340250552%2FFunctions%2F-134779887) | [jvm]<br>open fun [inUnexpectedNewRoom](../-pursuing/index.html#-1340250552%2FFunctions%2F-134779887)(previousRoom: [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.html), expectedNewRoom: [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.html), actualNewRoom: [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.html))<br>This is called in place of [inNewRoom](../../it.unibo.alchemist.model.interfaces/-navigation-strategy/in-new-room.html) when the pedestrian ends up in an unexpected room while moving. |


## Properties


| Name | Summary |
|---|---|
| [action](action.html) | [jvm]<br>open override val [action](action.html): [NavigationAction2D](../../it.unibo.alchemist.model.interfaces/index.html#-517309547%2FClasslikes%2F-134779887)<[T](index.html), [L](index.html), [R](index.html), [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.html), [Euclidean2DPassage](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d.graph/-euclidean2-d-passage/index.html)><br>The NavigationAction used to navigate the environment. |


## Inheritors


| Name |
|---|
| [GoalOrientedExploring](../-goal-oriented-exploring/index.html) |
| [Pursuing](../-pursuing/index.html) |

