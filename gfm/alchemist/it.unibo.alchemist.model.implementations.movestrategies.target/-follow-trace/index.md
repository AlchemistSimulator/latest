//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.movestrategies.target](../index.md)/[FollowTrace](index.md)

# FollowTrace

[jvm]\
class [FollowTrace](index.md) : [AbstractStrategyWithGPS](../../it.unibo.alchemist.model.implementations.movestrategies/-abstract-strategy-with-g-p-s/index.md), [TargetSelectionStrategy](../../it.unibo.alchemist.model.interfaces.movestrategies/-target-selection-strategy/index.md)<[GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md)> 

This strategy follows a [Route](../../it.unibo.alchemist.model.interfaces/-route/index.md).

## Constructors

| | |
|---|---|
| [FollowTrace](-follow-trace.md) | [jvm]<br>open fun [FollowTrace](-follow-trace.md)(reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>)<br>the reaction |

## Functions

| Name | Summary |
|---|---|
| [getTarget](get-target.md) | [jvm]<br>open fun [getTarget](get-target.md)(): [GPSPoint](../../it.unibo.alchemist.model.interfaces/-g-p-s-point/index.md) |
| [setTrace](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-straight-line-trace-dependant-speed/index.md#2080248117%2FFunctions%2F-267951372) | [jvm]<br>fun [setTrace](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-straight-line-trace-dependant-speed/index.md#2080248117%2FFunctions%2F-267951372)(trace: [GPSTrace](../../it.unibo.alchemist.model.interfaces/-g-p-s-trace/index.md))<br>abstract fun [setTrace](../../it.unibo.alchemist.model.interfaces/-object-with-g-p-s/set-trace.md)(trace: [GPSTrace](../../it.unibo.alchemist.model.interfaces/-g-p-s-trace/index.md))<br>the [GPSTrace](../../it.unibo.alchemist.model.interfaces/-g-p-s-trace/index.md) to follow |
