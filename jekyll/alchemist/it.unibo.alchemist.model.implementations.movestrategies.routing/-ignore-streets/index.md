---
title: IgnoreStreets
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.movestrategies.routing](../index.html)/[IgnoreStreets](index.html)



# IgnoreStreets



[jvm]\
class [IgnoreStreets](index.html)<[P](index.html) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<[P](../../it.unibo.alchemist.model.interfaces/-timed-route/index.html)>?> : [RoutingStrategy](../../it.unibo.alchemist.model.interfaces.movestrategies/-routing-strategy/index.html)<[P](../../it.unibo.alchemist.model.interfaces/-timed-route/index.html)> 

This strategy ignores any information about the map, and connects the starting and ending point with a straight line using [PolygonalChain](../../it.unibo.alchemist.model.implementations.routes/-polygonal-chain/index.html).



## Parameters


jvm

| | |
|---|---|
| <P> | position type |



## Functions


| Name | Summary |
|---|---|
| [computeRoute](compute-route.html) | [jvm]<br>open fun [computeRoute](compute-route.html)(currentPos: [P](../../it.unibo.alchemist.model.interfaces/-timed-route/index.html), finalPos: [P](../../it.unibo.alchemist.model.interfaces/-timed-route/index.html)): [Route](../../it.unibo.alchemist.model.interfaces/-route/index.html)<[P](../../it.unibo.alchemist.model.interfaces/-timed-route/index.html)> |

