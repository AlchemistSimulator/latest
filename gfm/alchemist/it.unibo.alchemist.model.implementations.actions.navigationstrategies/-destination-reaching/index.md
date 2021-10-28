//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.actions.navigationstrategies](../index.md)/[DestinationReaching](index.md)

# DestinationReaching

[jvm]\
open class [DestinationReaching](index.md)<[T](index.md), [L](index.md) : [Euclidean2DConvexShape](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/index.md#-786369621%2FClasslikes%2F-267951372), [R](index.md)>(**action**: [NavigationAction2D](../../it.unibo.alchemist.model.interfaces/index.md#-517309547%2FClasslikes%2F-267951372)<[T](index.md), [L](index.md), [R](index.md), [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.md), [Euclidean2DPassage](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d.graph/-euclidean2-d-passage/index.md)>, **knownDestinations**: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)>, **unknownDestinations**: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)>) : [GoalOrientedExploring](../-goal-oriented-exploring/index.md)<[T](index.md), [L](index.md), [R](index.md)> 

A [NavigationStrategy](../../it.unibo.alchemist.model.interfaces/-navigation-strategy/index.md) allowing to reach a (static) destination. The client can specify a list of knownDestinations (see [Pursuing](../-pursuing/index.md)) and unknownDestinations (see [GoalOrientedExploring](../-goal-oriented-exploring/index.md)). The pedestrian will try to reach the closest known destination for which a valid path leading there is known, but in case another destination is found along the way (either known or unknown), the latter will be approached instead of the chosen known destination. To put it in another way, this behavior mixes [KnownDestinationReaching](../-known-destination-reaching/index.md) and [GoalOrientedExploring](../-goal-oriented-exploring/index.md).

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
| [DestinationReaching](-destination-reaching.md) | [jvm]<br>fun [DestinationReaching](-destination-reaching.md)(action: [NavigationAction2D](../../it.unibo.alchemist.model.interfaces/index.md#-517309547%2FClasslikes%2F-267951372)<[T](index.md), [L](index.md), [R](index.md), [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.md), [Euclidean2DPassage](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d.graph/-euclidean2-d-passage/index.md)>, knownDestinations: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)>, unknownDestinations: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)> = emptyList())<br>the concentration type. |

## Functions

| Name | Summary |
|---|---|
| [inNewRoom](in-new-room.md) | [jvm]<br>open override fun [inNewRoom](in-new-room.md)(newRoom: [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.md))<br>This is called whenever the pedestrian enters a new room. |
| [inUnexpectedNewRoom](../-pursuing/index.md#-1340250552%2FFunctions%2F-267951372) | [jvm]<br>open fun [inUnexpectedNewRoom](../-pursuing/index.md#-1340250552%2FFunctions%2F-267951372)(previousRoom: [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.md), expectedNewRoom: [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.md), actualNewRoom: [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.md))<br>This is called in place of [inNewRoom](../../it.unibo.alchemist.model.interfaces/-navigation-strategy/in-new-room.md) when the pedestrian ends up in an unexpected room while moving. |

## Properties

| Name | Summary |
|---|---|
| [action](index.md#1520874878%2FProperties%2F-267951372) | [jvm]<br>open override val [action](index.md#1520874878%2FProperties%2F-267951372): [NavigationAction2D](../../it.unibo.alchemist.model.interfaces/index.md#-517309547%2FClasslikes%2F-267951372)<[T](index.md), [L](index.md), [R](index.md), [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.md), [Euclidean2DPassage](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d.graph/-euclidean2-d-passage/index.md)><br>The NavigationAction used to navigate the environment. |
