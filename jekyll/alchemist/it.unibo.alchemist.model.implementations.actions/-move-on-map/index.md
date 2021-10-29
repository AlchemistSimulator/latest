---
title: MoveOnMap
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.actions](../index.html)/[MoveOnMap](index.html)



# MoveOnMap



[jvm]\
open class [MoveOnMap](index.html)<[T](index.html)> : [AbstractConfigurableMoveNode](../-abstract-configurable-move-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-routing-trace-dependant-speed/index.html), [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)>



## Parameters


jvm

| | |
|---|---|
| <T> | concentration type |



## Constructors


| | |
|---|---|
| [MoveOnMap](-move-on-map.html) | [jvm]<br>open fun [MoveOnMap](-move-on-map.html)(environment: [MapEnvironment](../../it.unibo.alchemist.model.interfaces/-map-environment/index.html)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-routing-trace-dependant-speed/index.html)>, node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-routing-trace-dependant-speed/index.html)>, routingStrategy: [RoutingStrategy](../../it.unibo.alchemist.model.interfaces.movestrategies/-routing-strategy/index.html)<[GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)>, speedSelectionStrategy: [SpeedSelectionStrategy](../../it.unibo.alchemist.model.interfaces.movestrategies/-speed-selection-strategy/index.html)<[GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)>, targetSelectionStrategy: [TargetSelectionStrategy](../../it.unibo.alchemist.model.interfaces.movestrategies/-target-selection-strategy/index.html)<[GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)>)<br>the environment |


## Functions


| Name | Summary |
|---|---|
| [cloneAction](clone-action.html) | [jvm]<br>open fun [cloneAction](clone-action.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-routing-trace-dependant-speed/index.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-routing-trace-dependant-speed/index.html)>): [MoveOnMap](index.html)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-routing-trace-dependant-speed/index.html)><br>Fails, can't be cloned. |
| [execute](../-abstract-move-node/execute.html) | [jvm]<br>open fun [execute](../-abstract-move-node/execute.html)() |
| [getContext](../-abstract-move-node/get-context.html) | [jvm]<br>fun [getContext](../-abstract-move-node/get-context.html)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.html) |
| [getEnvironment](get-environment.html) | [jvm]<br>fun [getEnvironment](get-environment.html)(): [MapEnvironment](../../it.unibo.alchemist.model.interfaces/-map-environment/index.html)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-routing-trace-dependant-speed/index.html)> |
| [getNextPosition](../-abstract-configurable-move-node/get-next-position.html) | [jvm]<br>fun [getNextPosition](../-abstract-configurable-move-node/get-next-position.html)(): [P](../../it.unibo.alchemist.model.interfaces/-timed-route/index.html) |
| [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.html) | [jvm]<br>fun [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.html)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)> |
| [toString](../-abstract-action/to-string.html) | [jvm]<br>open fun [toString](../-abstract-action/to-string.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |


## Inheritors


| Name |
|---|
| [SAPEREWalker](../-s-a-p-e-r-e-walker/index.html) |
| [SAPEREWalkerRiseGradient](../-s-a-p-e-r-e-walker-rise-gradient/index.html) |
| [MoveOnMapWithGPS](../-move-on-map-with-g-p-s/index.html) |
| [TargetWalker](../-target-walker/index.html) |

