---
title: RoutingTraceDependantSpeed
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.movestrategies.speed](../index.html)/[RoutingTraceDependantSpeed](index.html)



# RoutingTraceDependantSpeed



[jvm]\
class [RoutingTraceDependantSpeed](index.html)<[T](index.html)> : [TraceDependantSpeed](../-trace-dependant-speed/index.html)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.html)> 

This [TraceDependantSpeed](../-trace-dependant-speed/index.html) strategy computes the remaining distance by relying on maps data for a selected [Vehicle](../../it.unibo.alchemist.model.interfaces/-vehicle/index.html).



## Parameters


jvm

| | |
|---|---|
| <T> | concentration type |



## Constructors


| | |
|---|---|
| [RoutingTraceDependantSpeed](-routing-trace-dependant-speed.html) | [jvm]<br>open fun [RoutingTraceDependantSpeed](-routing-trace-dependant-speed.html)(environment: [MapEnvironment](../../it.unibo.alchemist.model.interfaces/-map-environment/index.html)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.html)>, node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.html)>, vehicle: [Vehicle](../../it.unibo.alchemist.model.interfaces/-vehicle/index.html))<br>the environment |


## Functions


| Name | Summary |
|---|---|
| [getNodeMovementLength](../-trace-dependant-speed/get-node-movement-length.html) | [jvm]<br>fun [getNodeMovementLength](../-trace-dependant-speed/get-node-movement-length.html)(target: [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>abstract fun [getNodeMovementLength](../../it.unibo.alchemist.model.interfaces.movestrategies/-speed-selection-strategy/get-node-movement-length.html)(p: [P](../../it.unibo.alchemist.model.implementations.movestrategies.routing/-ignore-streets/index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [setTrace](../-straight-line-trace-dependant-speed/index.html#2080248117%2FFunctions%2F-134779887) | [jvm]<br>fun [setTrace](../-straight-line-trace-dependant-speed/index.html#2080248117%2FFunctions%2F-134779887)(trace: [GPSTrace](../../it.unibo.alchemist.model.interfaces/-g-p-s-trace/index.html))<br>abstract fun [setTrace](../../it.unibo.alchemist.model.interfaces/-object-with-g-p-s/set-trace.html)(trace: [GPSTrace](../../it.unibo.alchemist.model.interfaces/-g-p-s-trace/index.html))<br>the [GPSTrace](../../it.unibo.alchemist.model.interfaces/-g-p-s-trace/index.html) to follow |

