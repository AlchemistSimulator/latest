---
title: Route
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces](../index.html)/[Route](index.html)



# Route



[jvm]\
interface [Route](index.html)<[P](index.html) : [Position](../-position/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>?> : [Iterable](https://docs.oracle.com/javase/8/docs/api/java/lang/Iterable.html)<[P](index.html)> , [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)



## Parameters


jvm

| | |
|---|---|
| <P> | type of Position followed by [Route](index.html) |



## Functions


| Name | Summary |
|---|---|
| [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-655675525%2FFunctions%2F-134779887) | [jvm]<br>open fun [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-655675525%2FFunctions%2F-134779887)(action: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |
| [getPoint](get-point.html) | [jvm]<br>abstract fun [getPoint](get-point.html)(step: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [P](index.html)<br>the step |
| [getPoints](get-points.html) | [jvm]<br>abstract fun [getPoints](get-points.html)(): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[P](index.html)><br>the route as list of [Position](../-position/index.html) |
| [iterator](../../it.unibo.alchemist.loader.variables/-arbitrary-variable/index.html#-1606146105%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [iterator](../../it.unibo.alchemist.loader.variables/-arbitrary-variable/index.html#-1606146105%2FFunctions%2F-134779887)(): [Iterator](https://docs.oracle.com/javase/8/docs/api/java/util/Iterator.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html)> |
| [length](length.html) | [jvm]<br>abstract fun [length](length.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>the length of the route |
| [size](size.html) | [jvm]<br>abstract fun [size](size.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>the number of points this route is made of |
| [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-677603448%2FFunctions%2F-134779887) | [jvm]<br>open fun [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-677603448%2FFunctions%2F-134779887)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html)> |
| [stream](stream.html) | [jvm]<br>abstract fun [stream](stream.html)(): [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html)<[P](index.html)><br>the route as stream of [Position](../-position/index.html) |


## Inheritors


| Name |
|---|
| [PolygonalChain](../../it.unibo.alchemist.model.implementations.routes/-polygonal-chain/index.html) |
| [TimedRoute](../-timed-route/index.html) |

