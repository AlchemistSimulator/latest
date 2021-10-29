//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.routes](../index.md)/[GPSTraceImpl](index.md)

# GPSTraceImpl

[jvm]\
class [GPSTraceImpl](index.md) : [PolygonalChain](../-polygonal-chain/index.md)<[GPSPoint](../../it.unibo.alchemist.model.interfaces/-g-p-s-point/index.md)> , [GPSTrace](../../it.unibo.alchemist.model.interfaces/-g-p-s-trace/index.md)

## Constructors

| | |
|---|---|
| [GPSTraceImpl](-g-p-s-trace-impl.md) | [jvm]<br>@[SafeVarargs](https://docs.oracle.com/javase/8/docs/api/java/lang/SafeVarargs.html)()<br>open fun [GPSTraceImpl](-g-p-s-trace-impl.md)(tr: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[GPSPoint](../../it.unibo.alchemist.model.interfaces/-g-p-s-point/index.md)>)<br>GPS points |
| [GPSTraceImpl](-g-p-s-trace-impl.md) | [jvm]<br>open fun [GPSTraceImpl](-g-p-s-trace-impl.md)(tr: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[GPSPoint](../../it.unibo.alchemist.model.interfaces/-g-p-s-point/index.md)>)<br>GPS points |

## Functions

| Name | Summary |
|---|---|
| [equals](../-polygonal-chain/equals.md) | [jvm]<br>fun [equals](../-polygonal-chain/equals.md)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-655675525%2FFunctions%2F-267951372) | [jvm]<br>open fun [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-655675525%2FFunctions%2F-267951372)(action: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |
| [getFinalPosition](get-final-position.md) | [jvm]<br>open fun [getFinalPosition](get-final-position.md)(): [GPSPoint](../../it.unibo.alchemist.model.interfaces/-g-p-s-point/index.md)<br>The final position of the trace |
| [getFinalTime](get-final-time.md) | [jvm]<br>open fun [getFinalTime](get-final-time.md)(): [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md)<br>the final time for this [GPSTrace](../../it.unibo.alchemist.model.interfaces/-g-p-s-trace/index.md) |
| [getInitialPosition](get-initial-position.md) | [jvm]<br>open fun [getInitialPosition](get-initial-position.md)(): [GPSPoint](../../it.unibo.alchemist.model.interfaces/-g-p-s-point/index.md)<br>The initial position of the trace |
| [getNextPosition](get-next-position.md) | [jvm]<br>open fun [getNextPosition](get-next-position.md)(time: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md)): [GPSPoint](../../it.unibo.alchemist.model.interfaces/-g-p-s-point/index.md)<br>the time |
| [getPoint](../-polygonal-chain/get-point.md) | [jvm]<br>fun [getPoint](../-polygonal-chain/get-point.md)(step: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [P](../../it.unibo.alchemist.loader.deployments/-deployment/index.md) |
| [getPoints](../-polygonal-chain/get-points.md) | [jvm]<br>fun [getPoints](../-polygonal-chain/get-points.md)(): ImmutableList<[P](../../it.unibo.alchemist.loader.deployments/-deployment/index.md)><br>abstract fun [getPoints](../../it.unibo.alchemist.model.interfaces/-route/get-points.md)(): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[P](../../it.unibo.alchemist.loader.deployments/-deployment/index.md)> |
| [getPreviousPosition](get-previous-position.md) | [jvm]<br>open fun [getPreviousPosition](get-previous-position.md)(time: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md)): [GPSPoint](../../it.unibo.alchemist.model.interfaces/-g-p-s-point/index.md)<br>the time |
| [getStartTime](get-start-time.md) | [jvm]<br>open fun [getStartTime](get-start-time.md)(): [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md)<br>the first time for this [GPSTrace](../../it.unibo.alchemist.model.interfaces/-g-p-s-trace/index.md) |
| [getTripTime](get-trip-time.md) | [jvm]<br>open fun [getTripTime](get-trip-time.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>the total trip time |
| [hashCode](../-polygonal-chain/hash-code.md) | [jvm]<br>fun [hashCode](../-polygonal-chain/hash-code.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [interpolate](interpolate.md) | [jvm]<br>open fun [interpolate](interpolate.md)(time: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md)): [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md)<br>the time |
| [iterator](../-polygonal-chain/iterator.md) | [jvm]<br>fun [iterator](../-polygonal-chain/iterator.md)(): [Iterator](https://docs.oracle.com/javase/8/docs/api/java/util/Iterator.html)<[P](../../it.unibo.alchemist.loader.deployments/-deployment/index.md)><br>abstract fun [iterator](../../it.unibo.alchemist.loader.variables/-arbitrary-variable/index.md#-1606146105%2FFunctions%2F-267951372)(): [Iterator](https://docs.oracle.com/javase/8/docs/api/java/util/Iterator.html)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.md)> |
| [length](../-polygonal-chain/length.md) | [jvm]<br>fun [length](../-polygonal-chain/length.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [size](../-polygonal-chain/size.md) | [jvm]<br>fun [size](../-polygonal-chain/size.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-677603448%2FFunctions%2F-267951372) | [jvm]<br>open fun [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-677603448%2FFunctions%2F-267951372)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.md)> |
| [startAt](start-at.md) | [jvm]<br>open fun [startAt](start-at.md)(time: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md)): [GPSTraceImpl](index.md)<br>the time at which the new trace should start |
| [stream](../-polygonal-chain/stream.md) | [jvm]<br>fun [stream](../-polygonal-chain/stream.md)(): [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html)<[P](../../it.unibo.alchemist.loader.deployments/-deployment/index.md)> |
| [toString](../-polygonal-chain/to-string.md) | [jvm]<br>open fun [toString](../-polygonal-chain/to-string.md)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |
