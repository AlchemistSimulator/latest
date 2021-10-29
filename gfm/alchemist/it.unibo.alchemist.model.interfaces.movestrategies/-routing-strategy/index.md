//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces.movestrategies](../index.md)/[RoutingStrategy](index.md)

# RoutingStrategy

[jvm]\
@[FunctionalInterface](https://docs.oracle.com/javase/8/docs/api/java/lang/FunctionalInterface.html)()

interface [RoutingStrategy](index.md)<[P](index.md) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<[P](../../it.unibo.alchemist.model.interfaces/-route/index.md)>?> : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)

Strategy interface describing how the routing between two points happens.

## Parameters

jvm

| | |
|---|---|
| <P> | position type |

## Functions

| Name | Summary |
|---|---|
| [computeRoute](compute-route.md) | [jvm]<br>abstract fun [computeRoute](compute-route.md)(currentPos: [P](../../it.unibo.alchemist.model.interfaces/-route/index.md), finalPos: [P](../../it.unibo.alchemist.model.interfaces/-route/index.md)): [Route](../../it.unibo.alchemist.model.interfaces/-route/index.md)<[P](../../it.unibo.alchemist.model.interfaces/-route/index.md)><br>Computes a route between two positions. |

## Inheritors

| Name |
|---|
| [IgnoreStreets](../../it.unibo.alchemist.model.implementations.movestrategies.routing/-ignore-streets/index.md) |
| [OnStreets](../../it.unibo.alchemist.model.implementations.movestrategies.routing/-on-streets/index.md) |
