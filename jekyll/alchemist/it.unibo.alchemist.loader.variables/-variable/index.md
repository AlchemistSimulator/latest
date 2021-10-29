---
title: Variable
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.loader.variables](../index.html)/[Variable](index.html)



# Variable



[jvm]\
interface [Variable](index.html)<[V](index.html) : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)?> : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html), [Iterable](https://docs.oracle.com/javase/8/docs/api/java/lang/Iterable.html)<[V](../-printable-variable/index.html)> 

A variable simulation value, that provides a range of values for batches, and a default value for single-shot runs.



## Parameters


jvm

| | |
|---|---|
| <V> | value typ of the variable |



## Functions


| Name | Summary |
|---|---|
| [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-655675525%2FFunctions%2F-134779887) | [jvm]<br>open fun [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-655675525%2FFunctions%2F-134779887)(action: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |
| [getDefault](get-default.html) | [jvm]<br>abstract fun [getDefault](get-default.html)(): [V](../-printable-variable/index.html)<br>the default value for this [Variable](index.html) |
| [iterator](iterator.html) | [jvm]<br>open fun [iterator](iterator.html)(): [Iterator](https://docs.oracle.com/javase/8/docs/api/java/util/Iterator.html)<[V](../-printable-variable/index.html)> |
| [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-677603448%2FFunctions%2F-134779887) | [jvm]<br>open fun [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-677603448%2FFunctions%2F-134779887)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[T](https://docs.oracle.com/javase/8/docs/api/java/lang/Iterable.html)> |
| [steps](steps.html) | [jvm]<br>open fun [steps](steps.html)(): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)<br>the number of different values this [Variable](index.html) may yield |
| [stream](stream.html) | [jvm]<br>abstract fun [stream](stream.html)(): [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html)<[V](../-printable-variable/index.html)><br>a view of the values of this variable as [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html). |


## Inheritors


| Name |
|---|
| [PrintableVariable](../-printable-variable/index.html) |

