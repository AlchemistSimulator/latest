---
title: GPSTraceImpl
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.routes](../index.html)/[GPSTraceImpl](index.html)



# GPSTraceImpl



[jvm]\
class [GPSTraceImpl](index.html) : [PolygonalChain](../-polygonal-chain/index.html)<[GPSPoint](../../it.unibo.alchemist.model.interfaces/-g-p-s-point/index.html)> , [GPSTrace](../../it.unibo.alchemist.model.interfaces/-g-p-s-trace/index.html)



## Constructors


| | |
|---|---|
| [GPSTraceImpl](-g-p-s-trace-impl.html) | [jvm]<br>@[SafeVarargs](https://docs.oracle.com/javase/8/docs/api/java/lang/SafeVarargs.html)()<br>open fun [GPSTraceImpl](-g-p-s-trace-impl.html)(tr: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[GPSPoint](../../it.unibo.alchemist.model.interfaces/-g-p-s-point/index.html)>)<br>GPS points |
| [GPSTraceImpl](-g-p-s-trace-impl.html) | [jvm]<br>open fun [GPSTraceImpl](-g-p-s-trace-impl.html)(tr: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[GPSPoint](../../it.unibo.alchemist.model.interfaces/-g-p-s-point/index.html)>)<br>GPS points |


## Functions


| Name | Summary |
|---|---|
| [equals](../-polygonal-chain/equals.html) | [jvm]<br>fun [equals](../-polygonal-chain/equals.html)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-655675525%2FFunctions%2F-134779887) | [jvm]<br>open fun [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-655675525%2FFunctions%2F-134779887)(action: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |
| [getFinalPosition](get-final-position.html) | [jvm]<br>open fun [getFinalPosition](get-final-position.html)(): [GPSPoint](../../it.unibo.alchemist.model.interfaces/-g-p-s-point/index.html)<br>The final position of the trace |
| [getFinalTime](get-final-time.html) | [jvm]<br>open fun [getFinalTime](get-final-time.html)(): [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html)<br>the final time for this [GPSTrace](../../it.unibo.alchemist.model.interfaces/-g-p-s-trace/index.html) |
| [getInitialPosition](get-initial-position.html) | [jvm]<br>open fun [getInitialPosition](get-initial-position.html)(): [GPSPoint](../../it.unibo.alchemist.model.interfaces/-g-p-s-point/index.html)<br>The initial position of the trace |
| [getNextPosition](get-next-position.html) | [jvm]<br>open fun [getNextPosition](get-next-position.html)(time: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html)): [GPSPoint](../../it.unibo.alchemist.model.interfaces/-g-p-s-point/index.html)<br>the time |
| [getPoint](../-polygonal-chain/get-point.html) | [jvm]<br>fun [getPoint](../-polygonal-chain/get-point.html)(step: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [P](../../it.unibo.alchemist.model.interfaces/-timed-route/index.html) |
| [getPoints](../-polygonal-chain/get-points.html) | [jvm]<br>fun [getPoints](../-polygonal-chain/get-points.html)(): ImmutableList<[P](../../it.unibo.alchemist.model.interfaces/-timed-route/index.html)><br>abstract fun [getPoints](../../it.unibo.alchemist.model.interfaces/-route/get-points.html)(): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[P](../../it.unibo.alchemist.model.interfaces/-timed-route/index.html)> |
| [getPreviousPosition](get-previous-position.html) | [jvm]<br>open fun [getPreviousPosition](get-previous-position.html)(time: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html)): [GPSPoint](../../it.unibo.alchemist.model.interfaces/-g-p-s-point/index.html)<br>the time |
| [getStartTime](get-start-time.html) | [jvm]<br>open fun [getStartTime](get-start-time.html)(): [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html)<br>the first time for this [GPSTrace](../../it.unibo.alchemist.model.interfaces/-g-p-s-trace/index.html) |
| [getTripTime](get-trip-time.html) | [jvm]<br>open fun [getTripTime](get-trip-time.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>the total trip time |
| [hashCode](../-polygonal-chain/hash-code.html) | [jvm]<br>fun [hashCode](../-polygonal-chain/hash-code.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [interpolate](interpolate.html) | [jvm]<br>open fun [interpolate](interpolate.html)(time: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html)): [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)<br>the time |
| [iterator](../-polygonal-chain/iterator.html) | [jvm]<br>fun [iterator](../-polygonal-chain/iterator.html)(): [Iterator](https://docs.oracle.com/javase/8/docs/api/java/util/Iterator.html)<[P](../../it.unibo.alchemist.model.interfaces/-timed-route/index.html)><br>abstract fun [iterator](../../it.unibo.alchemist.loader.variables/-arbitrary-variable/index.html#-1606146105%2FFunctions%2F-134779887)(): [Iterator](https://docs.oracle.com/javase/8/docs/api/java/util/Iterator.html)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-straight-line-trace-dependant-speed/index.html)> |
| [length](../-polygonal-chain/length.html) | [jvm]<br>fun [length](../-polygonal-chain/length.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [size](../-polygonal-chain/size.html) | [jvm]<br>fun [size](../-polygonal-chain/size.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-677603448%2FFunctions%2F-134779887) | [jvm]<br>open fun [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-677603448%2FFunctions%2F-134779887)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-straight-line-trace-dependant-speed/index.html)> |
| [startAt](start-at.html) | [jvm]<br>open fun [startAt](start-at.html)(time: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html)): [GPSTraceImpl](index.html)<br>the time at which the new trace should start |
| [stream](../-polygonal-chain/stream.html) | [jvm]<br>fun [stream](../-polygonal-chain/stream.html)(): [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html)<[P](../../it.unibo.alchemist.model.interfaces/-timed-route/index.html)> |
| [toString](../-polygonal-chain/to-string.html) | [jvm]<br>open fun [toString](../-polygonal-chain/to-string.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |

