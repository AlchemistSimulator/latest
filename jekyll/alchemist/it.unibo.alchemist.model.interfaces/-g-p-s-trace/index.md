---
title: GPSTrace
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces](../index.html)/[GPSTrace](index.html)



# GPSTrace



[jvm]\
interface [GPSTrace](index.html) : [TimedRoute](../-timed-route/index.html)<[GPSPoint](../-g-p-s-point/index.html)>



## Functions


| Name | Summary |
|---|---|
| [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-655675525%2FFunctions%2F-134779887) | [jvm]<br>open fun [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-655675525%2FFunctions%2F-134779887)(action: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |
| [getFinalPosition](get-final-position.html) | [jvm]<br>abstract fun [getFinalPosition](get-final-position.html)(): [GPSPoint](../-g-p-s-point/index.html)<br>The final position of the trace |
| [getFinalTime](get-final-time.html) | [jvm]<br>abstract fun [getFinalTime](get-final-time.html)(): [Time](../-time/index.html)<br>the final time for this [GPSTrace](index.html) |
| [getInitialPosition](get-initial-position.html) | [jvm]<br>abstract fun [getInitialPosition](get-initial-position.html)(): [GPSPoint](../-g-p-s-point/index.html)<br>The initial position of the trace |
| [getNextPosition](get-next-position.html) | [jvm]<br>abstract fun [getNextPosition](get-next-position.html)(time: [Time](../-time/index.html)): [GPSPoint](../-g-p-s-point/index.html)<br>the time |
| [getPoint](../-route/get-point.html) | [jvm]<br>abstract fun [getPoint](../-route/get-point.html)(p: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [P](../../it.unibo.alchemist.model.implementations.movestrategies.routing/-ignore-streets/index.html) |
| [getPoints](../-route/get-points.html) | [jvm]<br>abstract fun [getPoints](../-route/get-points.html)(): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[P](../../it.unibo.alchemist.model.implementations.movestrategies.routing/-ignore-streets/index.html)> |
| [getPreviousPosition](get-previous-position.html) | [jvm]<br>abstract fun [getPreviousPosition](get-previous-position.html)(time: [Time](../-time/index.html)): [GPSPoint](../-g-p-s-point/index.html)<br>the time |
| [getStartTime](get-start-time.html) | [jvm]<br>abstract fun [getStartTime](get-start-time.html)(): [Time](../-time/index.html)<br>the first time for this [GPSTrace](index.html) |
| [getTripTime](../-timed-route/get-trip-time.html) | [jvm]<br>abstract fun [getTripTime](../-timed-route/get-trip-time.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>the total trip time |
| [interpolate](interpolate.html) | [jvm]<br>abstract fun [interpolate](interpolate.html)(time: [Time](../-time/index.html)): [GeoPosition](../-geo-position/index.html)<br>the time |
| [iterator](../../it.unibo.alchemist.loader.variables/-arbitrary-variable/index.html#-1606146105%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [iterator](../../it.unibo.alchemist.loader.variables/-arbitrary-variable/index.html#-1606146105%2FFunctions%2F-134779887)(): [Iterator](https://docs.oracle.com/javase/8/docs/api/java/util/Iterator.html)<[T](https://docs.oracle.com/javase/8/docs/api/java/lang/Iterable.html)> |
| [length](../-route/length.html) | [jvm]<br>abstract fun [length](../-route/length.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [size](../-route/size.html) | [jvm]<br>abstract fun [size](../-route/size.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-677603448%2FFunctions%2F-134779887) | [jvm]<br>open fun [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-677603448%2FFunctions%2F-134779887)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[T](https://docs.oracle.com/javase/8/docs/api/java/lang/Iterable.html)> |
| [startAt](start-at.html) | [jvm]<br>abstract fun [startAt](start-at.html)(time: [Time](../-time/index.html)): [GPSTrace](index.html)<br>the time at which the new trace should start |
| [stream](../-route/stream.html) | [jvm]<br>abstract fun [stream](../-route/stream.html)(): [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html)<[P](../../it.unibo.alchemist.model.implementations.movestrategies.routing/-ignore-streets/index.html)> |


## Inheritors


| Name |
|---|
| [GPSTraceImpl](../../it.unibo.alchemist.model.implementations.routes/-g-p-s-trace-impl/index.html) |

