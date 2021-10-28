//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.movestrategies.speed](../index.md)/[TraceDependantSpeed](index.md)

# TraceDependantSpeed

[jvm]\
abstract class [TraceDependantSpeed](index.md)<[T](index.md)> : [AbstractStrategyWithGPS](../../it.unibo.alchemist.model.implementations.movestrategies/-abstract-strategy-with-g-p-s/index.md), [SpeedSelectionStrategy](../../it.unibo.alchemist.model.interfaces.movestrategies/-speed-selection-strategy/index.md)<[GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md)> 

This strategy dynamically tries to move the node adjusting its speed to synchronize the reaction rate and the traces data.

## Parameters

jvm

| | |
|---|---|
| <T> | concentration type |

## Constructors

| | |
|---|---|
| [TraceDependantSpeed](-trace-dependant-speed.md) | [jvm]<br>open fun [TraceDependantSpeed](-trace-dependant-speed.md)(environment: [MapEnvironment](../../it.unibo.alchemist.model.interfaces/-map-environment/index.md)<[T](https://docs.oracle.com/javase/8/docs/api/java/lang/Iterable.html)>, node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](https://docs.oracle.com/javase/8/docs/api/java/lang/Iterable.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](https://docs.oracle.com/javase/8/docs/api/java/lang/Iterable.html)>)<br>the environment |

## Functions

| Name | Summary |
|---|---|
| [getNodeMovementLength](get-node-movement-length.md) | [jvm]<br>fun [getNodeMovementLength](get-node-movement-length.md)(target: [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [setTrace](../-straight-line-trace-dependant-speed/index.md#2080248117%2FFunctions%2F-267951372) | [jvm]<br>fun [setTrace](../-straight-line-trace-dependant-speed/index.md#2080248117%2FFunctions%2F-267951372)(trace: [GPSTrace](../../it.unibo.alchemist.model.interfaces/-g-p-s-trace/index.md))<br>abstract fun [setTrace](../../it.unibo.alchemist.model.interfaces/-object-with-g-p-s/set-trace.md)(trace: [GPSTrace](../../it.unibo.alchemist.model.interfaces/-g-p-s-trace/index.md))<br>the [GPSTrace](../../it.unibo.alchemist.model.interfaces/-g-p-s-trace/index.md) to follow |

## Inheritors

| Name |
|---|
| [RoutingTraceDependantSpeed](../-routing-trace-dependant-speed/index.md) |
| [StraightLineTraceDependantSpeed](../-straight-line-trace-dependant-speed/index.md) |
