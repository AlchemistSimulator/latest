//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.gpsload.impl](../index.md)/[TraceLoader](index.md)

# TraceLoader

[jvm]\
class [TraceLoader](index.md) : [Iterable](https://docs.oracle.com/javase/8/docs/api/java/lang/Iterable.html)<[GPSTrace](../../it.unibo.alchemist.model.interfaces/-g-p-s-trace/index.md)>

## Constructors

| | |
|---|---|
| [TraceLoader](-trace-loader.md) | [jvm]<br>open fun [TraceLoader](-trace-loader.md)(path: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), cycle: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), normalizer: [GPSTimeAlignment](../../it.unibo.alchemist.boundary.gpsload.api/-g-p-s-time-alignment/index.md))<br>path with the gps tracks |
| [TraceLoader](-trace-loader.md) | [jvm]<br>open fun [TraceLoader](-trace-loader.md)(path: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), cycle: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), timeNormalizerClass: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), normalizerArgs: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>)<br>path with the gps tracks |
| [TraceLoader](-trace-loader.md) | [jvm]<br>open fun [TraceLoader](-trace-loader.md)(path: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), normalizer: [GPSTimeAlignment](../../it.unibo.alchemist.boundary.gpsload.api/-g-p-s-time-alignment/index.md))<br>path with the gps tracks |
| [TraceLoader](-trace-loader.md) | [jvm]<br>open fun [TraceLoader](-trace-loader.md)(path: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), timeNormalizerClass: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), normalizerArgs: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>)<br>path with the gps tracks |

## Functions

| Name | Summary |
|---|---|
| [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-655675525%2FFunctions%2F-267951372) | [jvm]<br>open fun [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-655675525%2FFunctions%2F-267951372)(action: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |
| [iterator](iterator.md) | [jvm]<br>@NotNull()<br>open fun [iterator](iterator.md)(): @NotNull()[Iterator](https://docs.oracle.com/javase/8/docs/api/java/util/Iterator.html)<[GPSTrace](../../it.unibo.alchemist.model.interfaces/-g-p-s-trace/index.md)> |
| [size](size.md) | [jvm]<br>open fun [size](size.md)(): [Optional](https://docs.oracle.com/javase/8/docs/api/java/util/Optional.html)<[Integer](https://docs.oracle.com/javase/8/docs/api/java/lang/Integer.html)><br>the number of traces loaded, Optional. |
| [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-677603448%2FFunctions%2F-267951372) | [jvm]<br>open fun [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-677603448%2FFunctions%2F-267951372)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[T](https://docs.oracle.com/javase/8/docs/api/java/lang/Iterable.html)> |
