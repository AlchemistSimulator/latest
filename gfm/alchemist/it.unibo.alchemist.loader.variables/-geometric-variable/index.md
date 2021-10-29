//[alchemist](../../../index.md)/[it.unibo.alchemist.loader.variables](../index.md)/[GeometricVariable](index.md)

# GeometricVariable

[jvm]\
class [GeometricVariable](index.md) : [PrintableVariable](../-printable-variable/index.md)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)> 

A variable ranging geometrically (exponentially) in a range. Ideal for log-scale comparisons. e.g. a [GeometricVariable](index.md) with minimum = 1, maximum = 100 and samples = 5 will range over [1, ~3.16, 10, ~31.62 100]. Both min and max must be strictly bigger than 0.

## Constructors

| | |
|---|---|
| [GeometricVariable](-geometric-variable.md) | [jvm]<br>open fun [GeometricVariable](-geometric-variable.md)(def: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), min: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), max: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), samples: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>default value |

## Functions

| Name | Summary |
|---|---|
| [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-655675525%2FFunctions%2F-267951372) | [jvm]<br>open fun [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-655675525%2FFunctions%2F-267951372)(action: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |
| [getDefault](get-default.md) | [jvm]<br>open fun [getDefault](get-default.md)(): [Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)<br>the default value for this [Variable](../-variable/index.md) |
| [iterator](../-variable/iterator.md) | [jvm]<br>open fun [iterator](../-variable/iterator.md)(): [Iterator](https://docs.oracle.com/javase/8/docs/api/java/util/Iterator.html)<[V](../-printable-variable/index.md)><br>abstract fun [iterator](../-arbitrary-variable/index.md#-1606146105%2FFunctions%2F-267951372)(): [Iterator](https://docs.oracle.com/javase/8/docs/api/java/util/Iterator.html)<[T](../../it.unibo.alchemist.loader.export/-exporter/index.md)> |
| [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-677603448%2FFunctions%2F-267951372) | [jvm]<br>open fun [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-677603448%2FFunctions%2F-267951372)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[T](../../it.unibo.alchemist.loader.export/-exporter/index.md)> |
| [steps](../-variable/steps.md) | [jvm]<br>open fun [steps](../-variable/steps.md)(): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)<br>the number of different values this [Variable](../-variable/index.md) may yield |
| [stream](stream.md) | [jvm]<br>open fun [stream](stream.md)(): [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)><br>a view of the values of this variable as [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html). |
| [toString](to-string.md) | [jvm]<br>open fun [toString](to-string.md)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |
