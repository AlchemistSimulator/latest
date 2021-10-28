---
title: GraphHopperRoute
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.routes](../index.html)/[GraphHopperRoute](index.html)



# GraphHopperRoute



[jvm]\
class [GraphHopperRoute](index.html) : [TimedRoute](../../it.unibo.alchemist.model.interfaces/-timed-route/index.html)<[GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)>



## Constructors


| | |
|---|---|
| [GraphHopperRoute](-graph-hopper-route.html) | [jvm]<br>open fun [GraphHopperRoute](-graph-hopper-route.html)(response: GHResponse)<br>the response to use |


## Functions


| Name | Summary |
|---|---|
| [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-655675525%2FFunctions%2F-134779887) | [jvm]<br>open fun [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-655675525%2FFunctions%2F-134779887)(action: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |
| [getPoint](get-point.html) | [jvm]<br>open fun [getPoint](get-point.html)(step: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html) |
| [getPoints](../../it.unibo.alchemist.model.interfaces/-route/get-points.html) | [jvm]<br>abstract fun [getPoints](../../it.unibo.alchemist.model.interfaces/-route/get-points.html)(): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[P](../../it.unibo.alchemist.loader.deployments/-deployment/index.html)> |
| [getTripTime](get-trip-time.html) | [jvm]<br>open fun [getTripTime](get-trip-time.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>the total trip time |
| [iterator](iterator.html) | [jvm]<br>open fun [iterator](iterator.html)(): [Iterator](https://docs.oracle.com/javase/8/docs/api/java/util/Iterator.html)<[GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)> |
| [length](length.html) | [jvm]<br>open fun [length](length.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [size](size.html) | [jvm]<br>open fun [size](size.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-677603448%2FFunctions%2F-134779887) | [jvm]<br>open fun [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-677603448%2FFunctions%2F-134779887)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.target/-follow-target-on-map/index.html)> |
| [stream](stream.html) | [jvm]<br>open fun [stream](stream.html)(): [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html)<[GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)> |


## Properties


| Name | Summary |
|---|---|
| [points](points.html) | [jvm]<br>private val [points](points.html): ImmutableList<[GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)> |

