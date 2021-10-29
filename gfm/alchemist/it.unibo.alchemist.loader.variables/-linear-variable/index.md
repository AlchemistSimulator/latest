//[alchemist](../../../index.md)/[it.unibo.alchemist.loader.variables](../index.md)/[LinearVariable](index.md)

# LinearVariable

[jvm]\
class [LinearVariable](index.md) : [PrintableVariable](../-printable-variable/index.md)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)> 

This class represents a linear variable, namely a variable whose values span linearly between minimum and maximum.

## Constructors

| | |
|---|---|
| [LinearVariable](-linear-variable.md) | [jvm]<br>open fun [LinearVariable](-linear-variable.md)(def: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), min: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), max: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), step: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>default value |

## Functions

| Name | Summary |
|---|---|
| [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-655675525%2FFunctions%2F-267951372) | [jvm]<br>open fun [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-655675525%2FFunctions%2F-267951372)(action: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |
| [getDefault](get-default.md) | [jvm]<br>open fun [getDefault](get-default.md)(): [Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)<br>the default value for this [Variable](../-variable/index.md) |
| [iterator](../-variable/iterator.md) | [jvm]<br>open fun [iterator](../-variable/iterator.md)(): [Iterator](https://docs.oracle.com/javase/8/docs/api/java/util/Iterator.html)<[V](../-printable-variable/index.md)><br>abstract fun [iterator](../-arbitrary-variable/index.md#-1606146105%2FFunctions%2F-267951372)(): [Iterator](https://docs.oracle.com/javase/8/docs/api/java/util/Iterator.html)<[T](../../it.unibo.alchemist.loader.export/-extractor/extract-data.md)> |
| [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-677603448%2FFunctions%2F-267951372) | [jvm]<br>open fun [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-677603448%2FFunctions%2F-267951372)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[T](../../it.unibo.alchemist.loader.export/-extractor/extract-data.md)> |
| [steps](steps.md) | [jvm]<br>open fun [steps](steps.md)(): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)<br>the number of different values this [Variable](../-variable/index.md) may yield |
| [stream](stream.md) | [jvm]<br>open fun [stream](stream.md)(): [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)><br>a view of the values of this variable as [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html). |
| [toString](../-printable-variable/to-string.md) | [jvm]<br>open fun [toString](../-printable-variable/to-string.md)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |
