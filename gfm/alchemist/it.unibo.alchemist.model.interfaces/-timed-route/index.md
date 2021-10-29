//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces](../index.md)/[TimedRoute](index.md)

# TimedRoute

[jvm]\
interface [TimedRoute](index.md)<[P](index.md) : [Position](../-position/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>?> : [Route](../-route/index.md)<[P](../../it.unibo.alchemist.loader.deployments/-deployment/index.md)> 

Route with total trip time to cross it.

## Parameters

jvm

| | |
|---|---|
| <P> | type of position in the route |

## Functions

| Name | Summary |
|---|---|
| [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-655675525%2FFunctions%2F-267951372) | [jvm]<br>open fun [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-655675525%2FFunctions%2F-267951372)(action: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |
| [getPoint](../-route/get-point.md) | [jvm]<br>abstract fun [getPoint](../-route/get-point.md)(p: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [P](../../it.unibo.alchemist.loader.deployments/-deployment/index.md) |
| [getPoints](../-route/get-points.md) | [jvm]<br>abstract fun [getPoints](../-route/get-points.md)(): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[P](../../it.unibo.alchemist.loader.deployments/-deployment/index.md)> |
| [getTripTime](get-trip-time.md) | [jvm]<br>abstract fun [getTripTime](get-trip-time.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>the total trip time |
| [iterator](../../it.unibo.alchemist.loader.variables/-arbitrary-variable/index.md#-1606146105%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [iterator](../../it.unibo.alchemist.loader.variables/-arbitrary-variable/index.md#-1606146105%2FFunctions%2F-267951372)(): [Iterator](https://docs.oracle.com/javase/8/docs/api/java/util/Iterator.html)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.md)> |
| [length](../-route/length.md) | [jvm]<br>abstract fun [length](../-route/length.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [size](../-route/size.md) | [jvm]<br>abstract fun [size](../-route/size.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-677603448%2FFunctions%2F-267951372) | [jvm]<br>open fun [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-677603448%2FFunctions%2F-267951372)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.md)> |
| [stream](../-route/stream.md) | [jvm]<br>abstract fun [stream](../-route/stream.md)(): [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html)<[P](../../it.unibo.alchemist.loader.deployments/-deployment/index.md)> |

## Inheritors

| Name |
|---|
| [GPSTrace](../-g-p-s-trace/index.md) |
| [GraphHopperRoute](../../it.unibo.alchemist.model.implementations.routes/-graph-hopper-route/index.md) |
