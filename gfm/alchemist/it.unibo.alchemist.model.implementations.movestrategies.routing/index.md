//[alchemist](../../index.md)/[it.unibo.alchemist.model.implementations.movestrategies.routing](index.md)

# Package it.unibo.alchemist.model.implementations.movestrategies.routing

## Types

| Name | Summary |
|---|---|
| [IgnoreStreets](-ignore-streets/index.md) | [jvm]<br>class [IgnoreStreets](-ignore-streets/index.md)<[P](-ignore-streets/index.md) : [Position](../it.unibo.alchemist.model.interfaces/-position/index.md)<[P](../it.unibo.alchemist.model.interfaces/-timed-route/index.md)>?> : [RoutingStrategy](../it.unibo.alchemist.model.interfaces.movestrategies/-routing-strategy/index.md)<[P](../it.unibo.alchemist.model.interfaces/-timed-route/index.md)> <br>This strategy ignores any information about the map, and connects the starting and ending point with a straight line using [PolygonalChain](../it.unibo.alchemist.model.implementations.routes/-polygonal-chain/index.md). |
| [OnStreets](-on-streets/index.md) | [jvm]<br>class [OnStreets](-on-streets/index.md)<[T](-on-streets/index.md)> : [RoutingStrategy](../it.unibo.alchemist.model.interfaces.movestrategies/-routing-strategy/index.md)<[GeoPosition](../it.unibo.alchemist.model.interfaces/-geo-position/index.md)> <br>This strategy computes a route along streets allowed for a selected [Vehicle](../it.unibo.alchemist.model.interfaces/-vehicle/index.md) connecting the starting and ending point. |
