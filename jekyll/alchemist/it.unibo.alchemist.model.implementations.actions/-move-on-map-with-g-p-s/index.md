---
title: MoveOnMapWithGPS
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.actions](../index.html)/[MoveOnMapWithGPS](index.html)



# MoveOnMapWithGPS



[jvm]\
open class [MoveOnMapWithGPS](index.html)<[T](index.html)> : [MoveOnMap](../-move-on-map/index.html)<[T](../-reproduce-g-p-s-trace/index.html)> 

basic action that follow a [GPSTrace](../../it.unibo.alchemist.model.interfaces/-g-p-s-trace/index.html).



## Parameters


jvm

| | |
|---|---|
| <T> | concentration type |



## Constructors


| | |
|---|---|
| [MoveOnMapWithGPS](-move-on-map-with-g-p-s.html) | [jvm]<br>open fun [MoveOnMapWithGPS](-move-on-map-with-g-p-s.html)(environment: [MapEnvironment](../../it.unibo.alchemist.model.interfaces/-map-environment/index.html)<[T](../-reproduce-g-p-s-trace/index.html)>, node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../-reproduce-g-p-s-trace/index.html)>, rt: [RoutingStrategy](../../it.unibo.alchemist.model.interfaces.movestrategies/-routing-strategy/index.html)<[GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)>, sp: [SpeedSelectionStrategy](../../it.unibo.alchemist.model.interfaces.movestrategies/-speed-selection-strategy/index.html)<[GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)>, tg: [TargetSelectionStrategy](../../it.unibo.alchemist.model.interfaces.movestrategies/-target-selection-strategy/index.html)<[GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)>, path: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), cycle: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), normalizer: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), normalizerArgs: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>)<br>the environment |
| [MoveOnMapWithGPS](-move-on-map-with-g-p-s.html) | [jvm]<br>open fun [MoveOnMapWithGPS](-move-on-map-with-g-p-s.html)(environment: [MapEnvironment](../../it.unibo.alchemist.model.interfaces/-map-environment/index.html)<[T](../-reproduce-g-p-s-trace/index.html)>, node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../-reproduce-g-p-s-trace/index.html)>, rt: [RoutingStrategy](../../it.unibo.alchemist.model.interfaces.movestrategies/-routing-strategy/index.html)<[GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)>, sp: [SpeedSelectionStrategy](../../it.unibo.alchemist.model.interfaces.movestrategies/-speed-selection-strategy/index.html)<[GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)>, tg: [TargetSelectionStrategy](../../it.unibo.alchemist.model.interfaces.movestrategies/-target-selection-strategy/index.html)<[GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)>, trace: [GPSTrace](../../it.unibo.alchemist.model.interfaces/-g-p-s-trace/index.html))<br>the environment |


## Functions


| Name | Summary |
|---|---|
| [cloneAction](../-move-on-map/clone-action.html) | [jvm]<br>open fun [cloneAction](../-move-on-map/clone-action.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../-reproduce-g-p-s-trace/index.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../-reproduce-g-p-s-trace/index.html)>): [MoveOnMap](../-move-on-map/index.html)<[T](../-reproduce-g-p-s-trace/index.html)><br>Fails, can't be cloned.<br>[jvm]<br>abstract fun [cloneAction](../../it.unibo.alchemist.model.interfaces/-action/clone-action.html)(p: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../-reproduce-g-p-s-trace/index.html)>, p1: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../-reproduce-g-p-s-trace/index.html)>): [Action](../../it.unibo.alchemist.model.interfaces/-action/index.html)<[T](../-reproduce-g-p-s-trace/index.html)> |
| [execute](../-abstract-move-node/execute.html) | [jvm]<br>open fun [execute](../-abstract-move-node/execute.html)() |
| [getContext](../-abstract-move-node/get-context.html) | [jvm]<br>fun [getContext](../-abstract-move-node/get-context.html)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.html) |
| [getEnvironment](../-move-on-map/get-environment.html) | [jvm]<br>fun [getEnvironment](../-move-on-map/get-environment.html)(): [MapEnvironment](../../it.unibo.alchemist.model.interfaces/-map-environment/index.html)<[T](../-reproduce-g-p-s-trace/index.html)> |
| [getNextPosition](../-abstract-configurable-move-node/get-next-position.html) | [jvm]<br>fun [getNextPosition](../-abstract-configurable-move-node/get-next-position.html)(): [P](../-abstract-configurable-move-node/index.html) |
| [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.html) | [jvm]<br>fun [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.html)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)> |
| [toString](../-abstract-action/to-string.html) | [jvm]<br>open fun [toString](../-abstract-action/to-string.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |
| [traceFor](trace-for.html) | [jvm]<br>open fun [traceFor](trace-for.html)(environment: [MapEnvironment](../../it.unibo.alchemist.model.interfaces/-map-environment/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, path: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), cycle: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), normalizer: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), normalizerArgs: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>): [GPSTrace](../../it.unibo.alchemist.model.interfaces/-g-p-s-trace/index.html)<br>the environment |


## Inheritors


| Name |
|---|
| [ReproduceGPSTrace](../-reproduce-g-p-s-trace/index.html) |
| [GPSTraceWalker](../-g-p-s-trace-walker/index.html) |

