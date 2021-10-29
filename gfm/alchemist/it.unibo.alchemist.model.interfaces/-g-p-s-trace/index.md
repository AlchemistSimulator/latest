//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces](../index.md)/[GPSTrace](index.md)

# GPSTrace

[jvm]\
interface [GPSTrace](index.md) : [TimedRoute](../-timed-route/index.md)<[GPSPoint](../-g-p-s-point/index.md)>

## Functions

| Name | Summary |
|---|---|
| [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-655675525%2FFunctions%2F-267951372) | [jvm]<br>open fun [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-655675525%2FFunctions%2F-267951372)(action: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |
| [getFinalPosition](get-final-position.md) | [jvm]<br>abstract fun [getFinalPosition](get-final-position.md)(): [GPSPoint](../-g-p-s-point/index.md)<br>The final position of the trace |
| [getFinalTime](get-final-time.md) | [jvm]<br>abstract fun [getFinalTime](get-final-time.md)(): [Time](../-time/index.md)<br>the final time for this [GPSTrace](index.md) |
| [getInitialPosition](get-initial-position.md) | [jvm]<br>abstract fun [getInitialPosition](get-initial-position.md)(): [GPSPoint](../-g-p-s-point/index.md)<br>The initial position of the trace |
| [getNextPosition](get-next-position.md) | [jvm]<br>abstract fun [getNextPosition](get-next-position.md)(time: [Time](../-time/index.md)): [GPSPoint](../-g-p-s-point/index.md)<br>the time |
| [getPoint](../-route/get-point.md) | [jvm]<br>abstract fun [getPoint](../-route/get-point.md)(p: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [P](../-timed-route/index.md) |
| [getPoints](../-route/get-points.md) | [jvm]<br>abstract fun [getPoints](../-route/get-points.md)(): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[P](../-timed-route/index.md)> |
| [getPreviousPosition](get-previous-position.md) | [jvm]<br>abstract fun [getPreviousPosition](get-previous-position.md)(time: [Time](../-time/index.md)): [GPSPoint](../-g-p-s-point/index.md)<br>the time |
| [getStartTime](get-start-time.md) | [jvm]<br>abstract fun [getStartTime](get-start-time.md)(): [Time](../-time/index.md)<br>the first time for this [GPSTrace](index.md) |
| [getTripTime](../-timed-route/get-trip-time.md) | [jvm]<br>abstract fun [getTripTime](../-timed-route/get-trip-time.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>the total trip time |
| [interpolate](interpolate.md) | [jvm]<br>abstract fun [interpolate](interpolate.md)(time: [Time](../-time/index.md)): [GeoPosition](../-geo-position/index.md)<br>the time |
| [iterator](../../it.unibo.alchemist.loader.variables/-arbitrary-variable/index.md#-1606146105%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [iterator](../../it.unibo.alchemist.loader.variables/-arbitrary-variable/index.md#-1606146105%2FFunctions%2F-267951372)(): [Iterator](https://docs.oracle.com/javase/8/docs/api/java/util/Iterator.html)<[T](https://docs.oracle.com/javase/8/docs/api/java/lang/Iterable.html)> |
| [length](../-route/length.md) | [jvm]<br>abstract fun [length](../-route/length.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [size](../-route/size.md) | [jvm]<br>abstract fun [size](../-route/size.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-677603448%2FFunctions%2F-267951372) | [jvm]<br>open fun [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-677603448%2FFunctions%2F-267951372)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[T](https://docs.oracle.com/javase/8/docs/api/java/lang/Iterable.html)> |
| [startAt](start-at.md) | [jvm]<br>abstract fun [startAt](start-at.md)(time: [Time](../-time/index.md)): [GPSTrace](index.md)<br>the time at which the new trace should start |
| [stream](../-route/stream.md) | [jvm]<br>abstract fun [stream](../-route/stream.md)(): [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html)<[P](../-timed-route/index.md)> |

## Inheritors

| Name |
|---|
| [GPSTraceImpl](../../it.unibo.alchemist.model.implementations.routes/-g-p-s-trace-impl/index.md) |
