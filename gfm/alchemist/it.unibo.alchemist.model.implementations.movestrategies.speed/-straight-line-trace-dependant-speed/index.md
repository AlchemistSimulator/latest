//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.movestrategies.speed](../index.md)/[StraightLineTraceDependantSpeed](index.md)

# StraightLineTraceDependantSpeed

[jvm]\
class [StraightLineTraceDependantSpeed](index.md)<[T](index.md)> : [TraceDependantSpeed](../-trace-dependant-speed/index.md)<[T](../-trace-dependant-speed/index.md)> 

This [TraceDependantSpeed](../-trace-dependant-speed/index.md) uses the distance between coordinates for estimating the distance.

## Parameters

jvm

| | |
|---|---|
| <T> | concentration type |

## Constructors

| | |
|---|---|
| [StraightLineTraceDependantSpeed](-straight-line-trace-dependant-speed.md) | [jvm]<br>open fun [StraightLineTraceDependantSpeed](-straight-line-trace-dependant-speed.md)(environment: [MapEnvironment](../../it.unibo.alchemist.model.interfaces/-map-environment/index.md)<[T](../-trace-dependant-speed/index.md)>, node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../-trace-dependant-speed/index.md)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](../-trace-dependant-speed/index.md)>)<br>the environment |

## Functions

| Name | Summary |
|---|---|
| [getNodeMovementLength](../-trace-dependant-speed/get-node-movement-length.md) | [jvm]<br>fun [getNodeMovementLength](../-trace-dependant-speed/get-node-movement-length.md)(target: [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>abstract fun [getNodeMovementLength](../../it.unibo.alchemist.model.interfaces.movestrategies/-speed-selection-strategy/get-node-movement-length.md)(p: [P](../../it.unibo.alchemist.model.interfaces/-timed-route/index.md)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [setTrace](index.md#2080248117%2FFunctions%2F-267951372) | [jvm]<br>fun [setTrace](index.md#2080248117%2FFunctions%2F-267951372)(trace: [GPSTrace](../../it.unibo.alchemist.model.interfaces/-g-p-s-trace/index.md))<br>abstract fun [setTrace](../../it.unibo.alchemist.model.interfaces/-object-with-g-p-s/set-trace.md)(trace: [GPSTrace](../../it.unibo.alchemist.model.interfaces/-g-p-s-trace/index.md))<br>the [GPSTrace](../../it.unibo.alchemist.model.interfaces/-g-p-s-trace/index.md) to follow |
