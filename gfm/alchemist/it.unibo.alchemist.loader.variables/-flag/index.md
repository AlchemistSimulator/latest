//[alchemist](../../../index.md)/[it.unibo.alchemist.loader.variables](../index.md)/[Flag](index.md)

# Flag

[jvm]\
class [Flag](index.md) : [PrintableVariable](../-printable-variable/index.md)<[Boolean](https://docs.oracle.com/javase/8/docs/api/java/lang/Boolean.html)> 

This variable is a flag. Being booleans not a valid data type in charts, this variable just outputs 0 and 1. This is equivalent to a [LinearVariable](../-linear-variable/index.md) with two samples ranging from 0 to 1.

## Constructors

| | |
|---|---|
| [Flag](-flag.md) | [jvm]<br>open fun [Flag](-flag.md)(def: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))<br>the default value |

## Functions

| Name | Summary |
|---|---|
| [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-655675525%2FFunctions%2F-267951372) | [jvm]<br>open fun [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-655675525%2FFunctions%2F-267951372)(action: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |
| [getDefault](get-default.md) | [jvm]<br>open fun [getDefault](get-default.md)(): [Boolean](https://docs.oracle.com/javase/8/docs/api/java/lang/Boolean.html)<br>the default value for this [Variable](../-variable/index.md) |
| [iterator](../-variable/iterator.md) | [jvm]<br>open fun [iterator](../-variable/iterator.md)(): [Iterator](https://docs.oracle.com/javase/8/docs/api/java/util/Iterator.html)<[V](../-printable-variable/index.md)><br>abstract fun [iterator](../-arbitrary-variable/index.md#-1606146105%2FFunctions%2F-267951372)(): [Iterator](https://docs.oracle.com/javase/8/docs/api/java/util/Iterator.html)<[T](https://docs.oracle.com/javase/8/docs/api/java/lang/Iterable.html)> |
| [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-677603448%2FFunctions%2F-267951372) | [jvm]<br>open fun [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-677603448%2FFunctions%2F-267951372)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[T](https://docs.oracle.com/javase/8/docs/api/java/lang/Iterable.html)> |
| [steps](../-variable/steps.md) | [jvm]<br>open fun [steps](../-variable/steps.md)(): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)<br>the number of different values this [Variable](../-variable/index.md) may yield |
| [stream](stream.md) | [jvm]<br>open fun [stream](stream.md)(): [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html)<[Boolean](https://docs.oracle.com/javase/8/docs/api/java/lang/Boolean.html)><br>a view of the values of this variable as [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html). |
| [toString](../-printable-variable/to-string.md) | [jvm]<br>open fun [toString](../-printable-variable/to-string.md)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |
