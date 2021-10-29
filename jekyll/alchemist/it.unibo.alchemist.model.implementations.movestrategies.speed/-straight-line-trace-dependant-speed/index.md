---
title: StraightLineTraceDependantSpeed
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.movestrategies.speed](../index.html)/[StraightLineTraceDependantSpeed](index.html)



# StraightLineTraceDependantSpeed



[jvm]\
class [StraightLineTraceDependantSpeed](index.html)<[T](index.html)> : [TraceDependantSpeed](../-trace-dependant-speed/index.html)<[T](../-trace-dependant-speed/index.html)> 

This [TraceDependantSpeed](../-trace-dependant-speed/index.html) uses the distance between coordinates for estimating the distance.



## Parameters


jvm

| | |
|---|---|
| <T> | concentration type |



## Constructors


| | |
|---|---|
| [StraightLineTraceDependantSpeed](-straight-line-trace-dependant-speed.html) | [jvm]<br>open fun [StraightLineTraceDependantSpeed](-straight-line-trace-dependant-speed.html)(environment: [MapEnvironment](../../it.unibo.alchemist.model.interfaces/-map-environment/index.html)<[T](../-trace-dependant-speed/index.html)>, node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../-trace-dependant-speed/index.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../-trace-dependant-speed/index.html)>)<br>the environment |


## Functions


| Name | Summary |
|---|---|
| [getNodeMovementLength](../-trace-dependant-speed/get-node-movement-length.html) | [jvm]<br>fun [getNodeMovementLength](../-trace-dependant-speed/get-node-movement-length.html)(target: [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>abstract fun [getNodeMovementLength](../../it.unibo.alchemist.model.interfaces.movestrategies/-speed-selection-strategy/get-node-movement-length.html)(p: [P](../../it.unibo.alchemist.model.interfaces/-timed-route/index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [setTrace](index.html#2080248117%2FFunctions%2F-134779887) | [jvm]<br>fun [setTrace](index.html#2080248117%2FFunctions%2F-134779887)(trace: [GPSTrace](../../it.unibo.alchemist.model.interfaces/-g-p-s-trace/index.html))<br>abstract fun [setTrace](../../it.unibo.alchemist.model.interfaces/-object-with-g-p-s/set-trace.html)(trace: [GPSTrace](../../it.unibo.alchemist.model.interfaces/-g-p-s-trace/index.html))<br>the [GPSTrace](../../it.unibo.alchemist.model.interfaces/-g-p-s-trace/index.html) to follow |

