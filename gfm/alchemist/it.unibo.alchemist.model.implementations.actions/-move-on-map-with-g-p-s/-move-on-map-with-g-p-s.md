//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.actions](../index.md)/[MoveOnMapWithGPS](index.md)/[MoveOnMapWithGPS](-move-on-map-with-g-p-s.md)

# MoveOnMapWithGPS

[jvm]\
open fun [MoveOnMapWithGPS](-move-on-map-with-g-p-s.md)(environment: [MapEnvironment](../../it.unibo.alchemist.model.interfaces/-map-environment/index.md)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.target/-follow-target-on-map/index.md)>, node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.target/-follow-target-on-map/index.md)>, rt: [RoutingStrategy](../../it.unibo.alchemist.model.interfaces.movestrategies/-routing-strategy/index.md)<[GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md)>, sp: [SpeedSelectionStrategy](../../it.unibo.alchemist.model.interfaces.movestrategies/-speed-selection-strategy/index.md)<[GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md)>, tg: [TargetSelectionStrategy](../../it.unibo.alchemist.model.interfaces.movestrategies/-target-selection-strategy/index.md)<[GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md)>, path: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), cycle: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), normalizer: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), normalizerArgs: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>)

## Parameters

jvm

| | |
|---|---|
| environment | the environment |
| node | the node |
| rt | the [RoutingStrategy](../../it.unibo.alchemist.model.interfaces.movestrategies/-routing-strategy/index.md) |
| sp | the [SpeedSelectionStrategy](../../it.unibo.alchemist.model.interfaces.movestrategies/-speed-selection-strategy/index.md) |
| tg | [TargetSelectionStrategy](../../it.unibo.alchemist.model.interfaces.movestrategies/-target-selection-strategy/index.md) |
| path | resource(file, directory, ...) with GPS trace |
| cycle | true if the traces have to be distributed cyclically |
| normalizer | name of the class that implement the strategy to normalize the time |
| normalizerArgs | Args to build normalize |

[jvm]\
open fun [MoveOnMapWithGPS](-move-on-map-with-g-p-s.md)(environment: [MapEnvironment](../../it.unibo.alchemist.model.interfaces/-map-environment/index.md)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.target/-follow-target-on-map/index.md)>, node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.target/-follow-target-on-map/index.md)>, rt: [RoutingStrategy](../../it.unibo.alchemist.model.interfaces.movestrategies/-routing-strategy/index.md)<[GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md)>, sp: [SpeedSelectionStrategy](../../it.unibo.alchemist.model.interfaces.movestrategies/-speed-selection-strategy/index.md)<[GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md)>, tg: [TargetSelectionStrategy](../../it.unibo.alchemist.model.interfaces.movestrategies/-target-selection-strategy/index.md)<[GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md)>, trace: [GPSTrace](../../it.unibo.alchemist.model.interfaces/-g-p-s-trace/index.md))

## Parameters

jvm

| | |
|---|---|
| environment | the environment |
| node | the node |
| rt | the [RoutingStrategy](../../it.unibo.alchemist.model.interfaces.movestrategies/-routing-strategy/index.md) |
| sp | the [SpeedSelectionStrategy](../../it.unibo.alchemist.model.interfaces.movestrategies/-speed-selection-strategy/index.md) |
| tg | [TargetSelectionStrategy](../../it.unibo.alchemist.model.interfaces.movestrategies/-target-selection-strategy/index.md) |
| trace | [to follow](../../it.unibo.alchemist.model.interfaces/-g-p-s-trace/index.md) |
