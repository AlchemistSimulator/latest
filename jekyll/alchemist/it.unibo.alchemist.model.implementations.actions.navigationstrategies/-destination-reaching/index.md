---
title: DestinationReaching
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.actions.navigationstrategies](../index.html)/[DestinationReaching](index.html)



# DestinationReaching



[jvm]\
open class [DestinationReaching](index.html)<[T](index.html), [L](index.html) : [Euclidean2DConvexShape](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/index.html#-786369621%2FClasslikes%2F-134779887), [R](index.html)>(**action**: [NavigationAction2D](../../it.unibo.alchemist.model.interfaces/index.html#-517309547%2FClasslikes%2F-134779887)<[T](index.html), [L](index.html), [R](index.html), [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.html), [Euclidean2DPassage](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d.graph/-euclidean2-d-passage/index.html)>, **knownDestinations**: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)>, **unknownDestinations**: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)>) : [GoalOrientedExploring](../-goal-oriented-exploring/index.html)<[T](index.html), [L](index.html), [R](index.html)> 

A [NavigationStrategy](../../it.unibo.alchemist.model.interfaces/-navigation-strategy/index.html) allowing to reach a (static) destination. The client can specify a list of knownDestinations (see [Pursuing](../-pursuing/index.html)) and unknownDestinations (see [GoalOrientedExploring](../-goal-oriented-exploring/index.html)). The pedestrian will try to reach the closest known destination for which a valid path leading there is known, but in case another destination is found along the way (either known or unknown), the latter will be approached instead of the chosen known destination. To put it in another way, this behavior mixes [KnownDestinationReaching](../-known-destination-reaching/index.html) and [GoalOrientedExploring](../-goal-oriented-exploring/index.html).



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
| [DestinationReaching](-destination-reaching.html) | [jvm]<br>fun [DestinationReaching](-destination-reaching.html)(action: [NavigationAction2D](../../it.unibo.alchemist.model.interfaces/index.html#-517309547%2FClasslikes%2F-134779887)<[T](index.html), [L](index.html), [R](index.html), [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.html), [Euclidean2DPassage](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d.graph/-euclidean2-d-passage/index.html)>, knownDestinations: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)>, unknownDestinations: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)> = emptyList())<br>the concentration type. |


## Functions


| Name | Summary |
|---|---|
| [inNewRoom](in-new-room.html) | [jvm]<br>open override fun [inNewRoom](in-new-room.html)(newRoom: [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.html))<br>This is called whenever the pedestrian enters a new room. |
| [inUnexpectedNewRoom](../-pursuing/index.html#-1340250552%2FFunctions%2F-134779887) | [jvm]<br>open fun [inUnexpectedNewRoom](../-pursuing/index.html#-1340250552%2FFunctions%2F-134779887)(previousRoom: [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.html), expectedNewRoom: [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.html), actualNewRoom: [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.html))<br>This is called in place of [inNewRoom](../../it.unibo.alchemist.model.interfaces/-navigation-strategy/in-new-room.html) when the pedestrian ends up in an unexpected room while moving. |


## Properties


| Name | Summary |
|---|---|
| [action](index.html#1520874878%2FProperties%2F-134779887) | [jvm]<br>open override val [action](index.html#1520874878%2FProperties%2F-134779887): [NavigationAction2D](../../it.unibo.alchemist.model.interfaces/index.html#-517309547%2FClasslikes%2F-134779887)<[T](index.html), [L](index.html), [R](index.html), [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.html), [Euclidean2DPassage](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d.graph/-euclidean2-d-passage/index.html)><br>The NavigationAction used to navigate the environment. |

