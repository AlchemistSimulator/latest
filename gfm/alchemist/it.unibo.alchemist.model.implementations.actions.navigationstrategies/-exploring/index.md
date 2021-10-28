//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.actions.navigationstrategies](../index.md)/[Exploring](index.md)

# Exploring

[jvm]\
open class [Exploring](index.md)<[T](index.md), [L](index.md) : [Euclidean2DConvexShape](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/index.md#-786369621%2FClasslikes%2F-267951372), [R](index.md)>(**action**: [NavigationAction2D](../../it.unibo.alchemist.model.interfaces/index.md#-517309547%2FClasslikes%2F-267951372)<[T](index.md), [L](index.md), [R](index.md), [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.md), [Euclidean2DPassage](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d.graph/-euclidean2-d-passage/index.md)>, **knownImpasseWeight**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) : [NavigationStrategy](../../it.unibo.alchemist.model.interfaces/-navigation-strategy/index.md)<[T](index.md), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md), [Euclidean2DTransformation](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-euclidean2-d-transformation/index.md), [L](index.md), [R](index.md), [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.md), [Euclidean2DPassage](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d.graph/-euclidean2-d-passage/index.md)> 

A [NavigationStrategy](../../it.unibo.alchemist.model.interfaces/-navigation-strategy/index.md) allowing to explore the environment. In order to choose which direction to take, a weighting system is used: every time the pedestrian enters a new room all the visible doors are weighted, the one with minimum weight is then crossed. The weighting system used here is derived from the one by [Andresen et al.](https://doi.org/10.1080/23249935.2018.1432717), see weight.

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
| [Exploring](-exploring.md) | [jvm]<br>fun [Exploring](-exploring.md)(action: [NavigationAction2D](../../it.unibo.alchemist.model.interfaces/index.md#-517309547%2FClasslikes%2F-267951372)<[T](index.md), [L](index.md), [R](index.md), [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.md), [Euclidean2DPassage](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d.graph/-euclidean2-d-passage/index.md)>, knownImpasseWeight: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = DEFAULT_IMPASSE_WEIGHT)<br>the concentration type. |

## Types

| Name | Summary |
|---|---|
| [Companion](-companion/index.md) | [jvm]<br>object [Companion](-companion/index.md) |

## Functions

| Name | Summary |
|---|---|
| [inNewRoom](in-new-room.md) | [jvm]<br>open override fun [inNewRoom](in-new-room.md)(newRoom: [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.md))<br>This is called whenever the pedestrian enters a new room. |
| [inUnexpectedNewRoom](../-pursuing/index.md#-1340250552%2FFunctions%2F-267951372) | [jvm]<br>open fun [inUnexpectedNewRoom](../-pursuing/index.md#-1340250552%2FFunctions%2F-267951372)(previousRoom: [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.md), expectedNewRoom: [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.md), actualNewRoom: [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.md))<br>This is called in place of [inNewRoom](../../it.unibo.alchemist.model.interfaces/-navigation-strategy/in-new-room.md) when the pedestrian ends up in an unexpected room while moving. |

## Properties

| Name | Summary |
|---|---|
| [action](action.md) | [jvm]<br>open override val [action](action.md): [NavigationAction2D](../../it.unibo.alchemist.model.interfaces/index.md#-517309547%2FClasslikes%2F-267951372)<[T](index.md), [L](index.md), [R](index.md), [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.md), [Euclidean2DPassage](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d.graph/-euclidean2-d-passage/index.md)><br>The NavigationAction used to navigate the environment. |

## Inheritors

| Name |
|---|
| [GoalOrientedExploring](../-goal-oriented-exploring/index.md) |
| [Pursuing](../-pursuing/index.md) |
