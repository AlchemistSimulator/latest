---
title: OnStreets
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.movestrategies.routing](../index.html)/[OnStreets](index.html)



# OnStreets



[jvm]\
class [OnStreets](index.html)<[T](index.html)> : [RoutingStrategy](../../it.unibo.alchemist.model.interfaces.movestrategies/-routing-strategy/index.html)<[GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)> 

This strategy computes a route along streets allowed for a selected [Vehicle](../../it.unibo.alchemist.model.interfaces/-vehicle/index.html) connecting the starting and ending point.



## Parameters


jvm

| | |
|---|---|
| <T> | concentration type |



## Constructors


| | |
|---|---|
| [OnStreets](-on-streets.html) | [jvm]<br>open fun [OnStreets](-on-streets.html)(environment: [MapEnvironment](../../it.unibo.alchemist.model.interfaces/-map-environment/index.html)<[T](../../it.unibo.alchemist.model.implementations.actions/-reproduce-g-p-s-trace/index.html)>, v: [Vehicle](../../it.unibo.alchemist.model.interfaces/-vehicle/index.html))<br>the environment |


## Functions


| Name | Summary |
|---|---|
| [computeRoute](compute-route.html) | [jvm]<br>open fun [computeRoute](compute-route.html)(currentPos: [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html), finalPos: [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)): [Route](../../it.unibo.alchemist.model.interfaces/-route/index.html)<[GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)> |

