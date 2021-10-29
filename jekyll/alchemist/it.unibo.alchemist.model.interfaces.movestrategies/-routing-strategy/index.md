---
title: RoutingStrategy
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces.movestrategies](../index.html)/[RoutingStrategy](index.html)



# RoutingStrategy



[jvm]\
@[FunctionalInterface](https://docs.oracle.com/javase/8/docs/api/java/lang/FunctionalInterface.html)()



interface [RoutingStrategy](index.html)<[P](index.html) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<[P](../../it.unibo.alchemist/-supported-incarnations/get.html)>?> : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)

Strategy interface describing how the routing between two points happens.



## Parameters


jvm

| | |
|---|---|
| <P> | position type |



## Functions


| Name | Summary |
|---|---|
| [computeRoute](compute-route.html) | [jvm]<br>abstract fun [computeRoute](compute-route.html)(currentPos: [P](../../it.unibo.alchemist/-supported-incarnations/get.html), finalPos: [P](../../it.unibo.alchemist/-supported-incarnations/get.html)): [Route](../../it.unibo.alchemist.model.interfaces/-route/index.html)<[P](../../it.unibo.alchemist/-supported-incarnations/get.html)><br>Computes a route between two positions. |


## Inheritors


| Name |
|---|
| [IgnoreStreets](../../it.unibo.alchemist.model.implementations.movestrategies.routing/-ignore-streets/index.html) |
| [OnStreets](../../it.unibo.alchemist.model.implementations.movestrategies.routing/-on-streets/index.html) |

