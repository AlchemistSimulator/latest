---
title: it.unibo.alchemist.model.implementations.movestrategies.routing
---
//[alchemist](../../index.html)/[it.unibo.alchemist.model.implementations.movestrategies.routing](index.html)



# Package it.unibo.alchemist.model.implementations.movestrategies.routing



## Types


| Name | Summary |
|---|---|
| [IgnoreStreets](-ignore-streets/index.html) | [jvm]<br>class [IgnoreStreets](-ignore-streets/index.html)<[P](-ignore-streets/index.html) : [Position](../it.unibo.alchemist.model.interfaces/-position/index.html)<[P](../it.unibo.alchemist.loader.deployments/-deployment/index.html)>?> : [RoutingStrategy](../it.unibo.alchemist.model.interfaces.movestrategies/-routing-strategy/index.html)<[P](../it.unibo.alchemist.loader.deployments/-deployment/index.html)> <br>This strategy ignores any information about the map, and connects the starting and ending point with a straight line using [PolygonalChain](../it.unibo.alchemist.model.implementations.routes/-polygonal-chain/index.html). |
| [OnStreets](-on-streets/index.html) | [jvm]<br>class [OnStreets](-on-streets/index.html)<[T](-on-streets/index.html)> : [RoutingStrategy](../it.unibo.alchemist.model.interfaces.movestrategies/-routing-strategy/index.html)<[GeoPosition](../it.unibo.alchemist.model.interfaces/-geo-position/index.html)> <br>This strategy computes a route along streets allowed for a selected [Vehicle](../it.unibo.alchemist.model.interfaces/-vehicle/index.html) connecting the starting and ending point. |

