//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces](../index.md)/[Route](index.md)

# Route

[jvm]\
interface [Route](index.md)<[P](index.md) : [Position](../-position/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>?> : [Iterable](https://docs.oracle.com/javase/8/docs/api/java/lang/Iterable.html)<[P](index.md)> , [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)

## Parameters

jvm

| | |
|---|---|
| <P> | type of Position followed by [Route](index.md) |

## Functions

| Name | Summary |
|---|---|
| [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-655675525%2FFunctions%2F-267951372) | [jvm]<br>open fun [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-655675525%2FFunctions%2F-267951372)(action: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |
| [getPoint](get-point.md) | [jvm]<br>abstract fun [getPoint](get-point.md)(step: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [P](index.md)<br>the step |
| [getPoints](get-points.md) | [jvm]<br>abstract fun [getPoints](get-points.md)(): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[P](index.md)><br>the route as list of [Position](../-position/index.md) |
| [iterator](../../it.unibo.alchemist.loader.variables/-arbitrary-variable/index.md#-1606146105%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [iterator](../../it.unibo.alchemist.loader.variables/-arbitrary-variable/index.md#-1606146105%2FFunctions%2F-267951372)(): [Iterator](https://docs.oracle.com/javase/8/docs/api/java/util/Iterator.html)<[T](../../it.unibo.alchemist.model.implementations.timedistributions/-weibull-distributed-weibull-time/index.md)> |
| [length](length.md) | [jvm]<br>abstract fun [length](length.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>the length of the route |
| [size](size.md) | [jvm]<br>abstract fun [size](size.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>the number of points this route is made of |
| [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-677603448%2FFunctions%2F-267951372) | [jvm]<br>open fun [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-677603448%2FFunctions%2F-267951372)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[T](../../it.unibo.alchemist.model.implementations.timedistributions/-weibull-distributed-weibull-time/index.md)> |
| [stream](stream.md) | [jvm]<br>abstract fun [stream](stream.md)(): [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html)<[P](index.md)><br>the route as stream of [Position](../-position/index.md) |

## Inheritors

| Name |
|---|
| [PolygonalChain](../../it.unibo.alchemist.model.implementations.routes/-polygonal-chain/index.md) |
| [TimedRoute](../-timed-route/index.md) |
