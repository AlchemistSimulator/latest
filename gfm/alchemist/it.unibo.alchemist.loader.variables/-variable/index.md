//[alchemist](../../../index.md)/[it.unibo.alchemist.loader.variables](../index.md)/[Variable](index.md)

# Variable

[jvm]\
interface [Variable](index.md)<[V](index.md) : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)?> : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html), [Iterable](https://docs.oracle.com/javase/8/docs/api/java/lang/Iterable.html)<[V](../-printable-variable/index.md)> 

A variable simulation value, that provides a range of values for batches, and a default value for single-shot runs.

## Parameters

jvm

| | |
|---|---|
| <V> | value typ of the variable |

## Functions

| Name | Summary |
|---|---|
| [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-655675525%2FFunctions%2F-267951372) | [jvm]<br>open fun [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-655675525%2FFunctions%2F-267951372)(action: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |
| [getDefault](get-default.md) | [jvm]<br>abstract fun [getDefault](get-default.md)(): [V](../-printable-variable/index.md)<br>the default value for this [Variable](index.md) |
| [iterator](iterator.md) | [jvm]<br>open fun [iterator](iterator.md)(): [Iterator](https://docs.oracle.com/javase/8/docs/api/java/util/Iterator.html)<[V](../-printable-variable/index.md)> |
| [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-677603448%2FFunctions%2F-267951372) | [jvm]<br>open fun [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-677603448%2FFunctions%2F-267951372)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[T](../../it.unibo.alchemist.loader.export/-mean-squared-error/index.md)> |
| [steps](steps.md) | [jvm]<br>open fun [steps](steps.md)(): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)<br>the number of different values this [Variable](index.md) may yield |
| [stream](stream.md) | [jvm]<br>abstract fun [stream](stream.md)(): [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html)<[V](../-printable-variable/index.md)><br>a view of the values of this variable as [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html). |

## Inheritors

| Name |
|---|
| [PrintableVariable](../-printable-variable/index.md) |
