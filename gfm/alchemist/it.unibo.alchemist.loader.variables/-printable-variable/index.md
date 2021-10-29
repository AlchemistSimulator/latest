//[alchemist](../../../index.md)/[it.unibo.alchemist.loader.variables](../index.md)/[PrintableVariable](index.md)

# PrintableVariable

[jvm]\
abstract class [PrintableVariable](index.md)<[V](index.md) : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)?> : [Variable](../-variable/index.md)<[V](index.md)> 

A variable stub, with a default [toString](to-string.md) method.

## Parameters

jvm

| | |
|---|---|
| <V> | value type of the variable |

## Functions

| Name | Summary |
|---|---|
| [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-655675525%2FFunctions%2F-267951372) | [jvm]<br>open fun [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-655675525%2FFunctions%2F-267951372)(action: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |
| [getDefault](../-variable/get-default.md) | [jvm]<br>abstract fun [getDefault](../-variable/get-default.md)(): [V](index.md)<br>the default value for this [Variable](../-variable/index.md) |
| [iterator](../-variable/iterator.md) | [jvm]<br>open fun [iterator](../-variable/iterator.md)(): [Iterator](https://docs.oracle.com/javase/8/docs/api/java/util/Iterator.html)<[V](index.md)><br>abstract fun [iterator](../-arbitrary-variable/index.md#-1606146105%2FFunctions%2F-267951372)(): [Iterator](https://docs.oracle.com/javase/8/docs/api/java/util/Iterator.html)<[T](../../it.unibo.alchemist.loader.export/-mean-squared-error/index.md)> |
| [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-677603448%2FFunctions%2F-267951372) | [jvm]<br>open fun [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-677603448%2FFunctions%2F-267951372)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[T](../../it.unibo.alchemist.loader.export/-mean-squared-error/index.md)> |
| [steps](../-variable/steps.md) | [jvm]<br>open fun [steps](../-variable/steps.md)(): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)<br>the number of different values this [Variable](../-variable/index.md) may yield |
| [stream](../-variable/stream.md) | [jvm]<br>abstract fun [stream](../-variable/stream.md)(): [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html)<[V](index.md)><br>a view of the values of this variable as [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html). |
| [toString](to-string.md) | [jvm]<br>open fun [toString](to-string.md)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |

## Inheritors

| Name |
|---|
| [GeometricVariable](../-geometric-variable/index.md) |
| [LinearVariable](../-linear-variable/index.md) |
| [Flag](../-flag/index.md) |
| [ArbitraryVariable](../-arbitrary-variable/index.md) |
