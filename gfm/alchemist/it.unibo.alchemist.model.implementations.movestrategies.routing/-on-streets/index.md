//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.movestrategies.routing](../index.md)/[OnStreets](index.md)

# OnStreets

[jvm]\
class [OnStreets](index.md)<[T](index.md)> : [RoutingStrategy](../../it.unibo.alchemist.model.interfaces.movestrategies/-routing-strategy/index.md)<[GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md)> 

This strategy computes a route along streets allowed for a selected [Vehicle](../../it.unibo.alchemist.model.interfaces/-vehicle/index.md) connecting the starting and ending point.

## Parameters

jvm

| | |
|---|---|
| <T> | concentration type |

## Constructors

| | |
|---|---|
| [OnStreets](-on-streets.md) | [jvm]<br>open fun [OnStreets](-on-streets.md)(environment: [MapEnvironment](../../it.unibo.alchemist.model.interfaces/-map-environment/index.md)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.md)>, v: [Vehicle](../../it.unibo.alchemist.model.interfaces/-vehicle/index.md))<br>the environment |

## Functions

| Name | Summary |
|---|---|
| [computeRoute](compute-route.md) | [jvm]<br>open fun [computeRoute](compute-route.md)(currentPos: [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md), finalPos: [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md)): [Route](../../it.unibo.alchemist.model.interfaces/-route/index.md)<[GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md)> |
