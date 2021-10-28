---
title: FollowTrace
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.movestrategies.target](../index.html)/[FollowTrace](index.html)



# FollowTrace



[jvm]\
class [FollowTrace](index.html) : [AbstractStrategyWithGPS](../../it.unibo.alchemist.model.implementations.movestrategies/-abstract-strategy-with-g-p-s/index.html), [TargetSelectionStrategy](../../it.unibo.alchemist.model.interfaces.movestrategies/-target-selection-strategy/index.html)<[GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)> 

This strategy follows a [Route](../../it.unibo.alchemist.model.interfaces/-route/index.html).



## Constructors


| | |
|---|---|
| [FollowTrace](-follow-trace.html) | [jvm]<br>open fun [FollowTrace](-follow-trace.html)(reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>)<br>the reaction |


## Functions


| Name | Summary |
|---|---|
| [getTarget](get-target.html) | [jvm]<br>open fun [getTarget](get-target.html)(): [GPSPoint](../../it.unibo.alchemist.model.interfaces/-g-p-s-point/index.html) |
| [setTrace](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-straight-line-trace-dependant-speed/index.html#2080248117%2FFunctions%2F-134779887) | [jvm]<br>fun [setTrace](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-straight-line-trace-dependant-speed/index.html#2080248117%2FFunctions%2F-134779887)(trace: [GPSTrace](../../it.unibo.alchemist.model.interfaces/-g-p-s-trace/index.html))<br>abstract fun [setTrace](../../it.unibo.alchemist.model.interfaces/-object-with-g-p-s/set-trace.html)(trace: [GPSTrace](../../it.unibo.alchemist.model.interfaces/-g-p-s-trace/index.html))<br>the [GPSTrace](../../it.unibo.alchemist.model.interfaces/-g-p-s-trace/index.html) to follow |

