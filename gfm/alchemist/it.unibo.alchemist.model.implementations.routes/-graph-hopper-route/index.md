//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.routes](../index.md)/[GraphHopperRoute](index.md)

# GraphHopperRoute

[jvm]\
class [GraphHopperRoute](index.md) : [TimedRoute](../../it.unibo.alchemist.model.interfaces/-timed-route/index.md)<[GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md)>

## Constructors

| | |
|---|---|
| [GraphHopperRoute](-graph-hopper-route.md) | [jvm]<br>open fun [GraphHopperRoute](-graph-hopper-route.md)(response: GHResponse)<br>the response to use |

## Functions

| Name | Summary |
|---|---|
| [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-655675525%2FFunctions%2F-267951372) | [jvm]<br>open fun [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-655675525%2FFunctions%2F-267951372)(action: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |
| [getPoint](get-point.md) | [jvm]<br>open fun [getPoint](get-point.md)(step: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md) |
| [getPoints](../../it.unibo.alchemist.model.interfaces/-route/get-points.md) | [jvm]<br>abstract fun [getPoints](../../it.unibo.alchemist.model.interfaces/-route/get-points.md)(): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[P](../../it.unibo.alchemist.model.interfaces/-timed-route/index.md)> |
| [getTripTime](get-trip-time.md) | [jvm]<br>open fun [getTripTime](get-trip-time.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>the total trip time |
| [iterator](iterator.md) | [jvm]<br>open fun [iterator](iterator.md)(): [Iterator](https://docs.oracle.com/javase/8/docs/api/java/util/Iterator.html)<[GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md)> |
| [length](length.md) | [jvm]<br>open fun [length](length.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [size](size.md) | [jvm]<br>open fun [size](size.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-677603448%2FFunctions%2F-267951372) | [jvm]<br>open fun [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-677603448%2FFunctions%2F-267951372)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.md)> |
| [stream](stream.md) | [jvm]<br>open fun [stream](stream.md)(): [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html)<[GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md)> |

## Properties

| Name | Summary |
|---|---|
| [points](points.md) | [jvm]<br>private val [points](points.md): ImmutableList<[GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md)> |
