//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.movestrategies.routing](../index.md)/[IgnoreStreets](index.md)

# IgnoreStreets

[jvm]\
class [IgnoreStreets](index.md)<[P](index.md) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<[P](../../it.unibo.alchemist.loader.deployments/-deployment/index.md)>?> : [RoutingStrategy](../../it.unibo.alchemist.model.interfaces.movestrategies/-routing-strategy/index.md)<[P](../../it.unibo.alchemist.loader.deployments/-deployment/index.md)> 

This strategy ignores any information about the map, and connects the starting and ending point with a straight line using [PolygonalChain](../../it.unibo.alchemist.model.implementations.routes/-polygonal-chain/index.md).

## Parameters

jvm

| | |
|---|---|
| <P> | position type |

## Functions

| Name | Summary |
|---|---|
| [computeRoute](compute-route.md) | [jvm]<br>open fun [computeRoute](compute-route.md)(currentPos: [P](../../it.unibo.alchemist.loader.deployments/-deployment/index.md), finalPos: [P](../../it.unibo.alchemist.loader.deployments/-deployment/index.md)): [Route](../../it.unibo.alchemist.model.interfaces/-route/index.md)<[P](../../it.unibo.alchemist.loader.deployments/-deployment/index.md)> |
