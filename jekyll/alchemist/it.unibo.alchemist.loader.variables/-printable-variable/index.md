---
title: PrintableVariable
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.loader.variables](../index.html)/[PrintableVariable](index.html)



# PrintableVariable



[jvm]\
abstract class [PrintableVariable](index.html)<[V](index.html) : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)?> : [Variable](../-variable/index.html)<[V](index.html)> 

A variable stub, with a default [toString](to-string.html) method.



## Parameters


jvm

| | |
|---|---|
| <V> | value type of the variable |



## Functions


| Name | Summary |
|---|---|
| [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-655675525%2FFunctions%2F-134779887) | [jvm]<br>open fun [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-655675525%2FFunctions%2F-134779887)(action: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |
| [getDefault](../-variable/get-default.html) | [jvm]<br>abstract fun [getDefault](../-variable/get-default.html)(): [V](index.html)<br>the default value for this [Variable](../-variable/index.html) |
| [iterator](../-variable/iterator.html) | [jvm]<br>open fun [iterator](../-variable/iterator.html)(): [Iterator](https://docs.oracle.com/javase/8/docs/api/java/util/Iterator.html)<[V](index.html)><br>abstract fun [iterator](../-arbitrary-variable/index.html#-1606146105%2FFunctions%2F-134779887)(): [Iterator](https://docs.oracle.com/javase/8/docs/api/java/util/Iterator.html)<[T](https://docs.oracle.com/javase/8/docs/api/java/lang/Iterable.html)> |
| [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-677603448%2FFunctions%2F-134779887) | [jvm]<br>open fun [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-677603448%2FFunctions%2F-134779887)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[T](https://docs.oracle.com/javase/8/docs/api/java/lang/Iterable.html)> |
| [steps](../-variable/steps.html) | [jvm]<br>open fun [steps](../-variable/steps.html)(): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)<br>the number of different values this [Variable](../-variable/index.html) may yield |
| [stream](../-variable/stream.html) | [jvm]<br>abstract fun [stream](../-variable/stream.html)(): [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html)<[V](index.html)><br>a view of the values of this variable as [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html). |
| [toString](to-string.html) | [jvm]<br>open fun [toString](to-string.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |


## Inheritors


| Name |
|---|
| [GeometricVariable](../-geometric-variable/index.html) |
| [LinearVariable](../-linear-variable/index.html) |
| [Flag](../-flag/index.html) |
| [ArbitraryVariable](../-arbitrary-variable/index.html) |
