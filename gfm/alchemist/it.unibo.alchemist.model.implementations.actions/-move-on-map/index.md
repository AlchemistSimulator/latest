//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.actions](../index.md)/[MoveOnMap](index.md)

# MoveOnMap

[jvm]\
open class [MoveOnMap](index.md)<[T](index.md)> : [AbstractConfigurableMoveNode](../-abstract-configurable-move-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.md), [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md)>

## Parameters

jvm

| | |
|---|---|
| <T> | concentration type |

## Constructors

| | |
|---|---|
| [MoveOnMap](-move-on-map.md) | [jvm]<br>open fun [MoveOnMap](-move-on-map.md)(environment: [MapEnvironment](../../it.unibo.alchemist.model.interfaces/-map-environment/index.md)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.md)>, node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.md)>, routingStrategy: [RoutingStrategy](../../it.unibo.alchemist.model.interfaces.movestrategies/-routing-strategy/index.md)<[GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md)>, speedSelectionStrategy: [SpeedSelectionStrategy](../../it.unibo.alchemist.model.interfaces.movestrategies/-speed-selection-strategy/index.md)<[GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md)>, targetSelectionStrategy: [TargetSelectionStrategy](../../it.unibo.alchemist.model.interfaces.movestrategies/-target-selection-strategy/index.md)<[GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md)>)<br>the environment |

## Functions

| Name | Summary |
|---|---|
| [cloneAction](clone-action.md) | [jvm]<br>open fun [cloneAction](clone-action.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.md)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.md)>): [MoveOnMap](index.md)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.md)><br>Fails, can't be cloned. |
| [execute](../-abstract-move-node/execute.md) | [jvm]<br>open fun [execute](../-abstract-move-node/execute.md)() |
| [getContext](../-abstract-move-node/get-context.md) | [jvm]<br>fun [getContext](../-abstract-move-node/get-context.md)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.md) |
| [getEnvironment](get-environment.md) | [jvm]<br>fun [getEnvironment](get-environment.md)(): [MapEnvironment](../../it.unibo.alchemist.model.interfaces/-map-environment/index.md)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.md)> |
| [getNextPosition](../-abstract-configurable-move-node/get-next-position.md) | [jvm]<br>fun [getNextPosition](../-abstract-configurable-move-node/get-next-position.md)(): [P](../../it.unibo.alchemist.model.interfaces/-timed-route/index.md) |
| [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.md) | [jvm]<br>fun [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.md)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.md)> |
| [toString](../-abstract-action/to-string.md) | [jvm]<br>open fun [toString](../-abstract-action/to-string.md)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |

## Inheritors

| Name |
|---|
| [SAPEREWalker](../-s-a-p-e-r-e-walker/index.md) |
| [SAPEREWalkerRiseGradient](../-s-a-p-e-r-e-walker-rise-gradient/index.md) |
| [MoveOnMapWithGPS](../-move-on-map-with-g-p-s/index.md) |
| [TargetWalker](../-target-walker/index.md) |
