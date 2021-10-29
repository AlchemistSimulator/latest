---
title: TraceDependantSpeed
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.movestrategies.speed](../index.html)/[TraceDependantSpeed](index.html)



# TraceDependantSpeed



[jvm]\
abstract class [TraceDependantSpeed](index.html)<[T](index.html)> : [AbstractStrategyWithGPS](../../it.unibo.alchemist.model.implementations.movestrategies/-abstract-strategy-with-g-p-s/index.html), [SpeedSelectionStrategy](../../it.unibo.alchemist.model.interfaces.movestrategies/-speed-selection-strategy/index.html)<[GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)> 

This strategy dynamically tries to move the node adjusting its speed to synchronize the reaction rate and the traces data.



## Parameters


jvm

| | |
|---|---|
| <T> | concentration type |



## Constructors


| | |
|---|---|
| [TraceDependantSpeed](-trace-dependant-speed.html) | [jvm]<br>open fun [TraceDependantSpeed](-trace-dependant-speed.html)(environment: [MapEnvironment](../../it.unibo.alchemist.model.interfaces/-map-environment/index.html)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.target/-follow-target-on-map/index.html)>, node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.target/-follow-target-on-map/index.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.target/-follow-target-on-map/index.html)>)<br>the environment |


## Functions


| Name | Summary |
|---|---|
| [getNodeMovementLength](get-node-movement-length.html) | [jvm]<br>fun [getNodeMovementLength](get-node-movement-length.html)(target: [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [setTrace](../-straight-line-trace-dependant-speed/index.html#2080248117%2FFunctions%2F-134779887) | [jvm]<br>fun [setTrace](../-straight-line-trace-dependant-speed/index.html#2080248117%2FFunctions%2F-134779887)(trace: [GPSTrace](../../it.unibo.alchemist.model.interfaces/-g-p-s-trace/index.html))<br>abstract fun [setTrace](../../it.unibo.alchemist.model.interfaces/-object-with-g-p-s/set-trace.html)(trace: [GPSTrace](../../it.unibo.alchemist.model.interfaces/-g-p-s-trace/index.html))<br>the [GPSTrace](../../it.unibo.alchemist.model.interfaces/-g-p-s-trace/index.html) to follow |


## Inheritors


| Name |
|---|
| [RoutingTraceDependantSpeed](../-routing-trace-dependant-speed/index.html) |
| [StraightLineTraceDependantSpeed](../-straight-line-trace-dependant-speed/index.html) |

