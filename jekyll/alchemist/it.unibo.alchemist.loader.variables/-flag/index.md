---
title: Flag
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.loader.variables](../index.html)/[Flag](index.html)



# Flag



[jvm]\
class [Flag](index.html) : [PrintableVariable](../-printable-variable/index.html)<[Boolean](https://docs.oracle.com/javase/8/docs/api/java/lang/Boolean.html)> 

This variable is a flag. Being booleans not a valid data type in charts, this variable just outputs 0 and 1. This is equivalent to a [LinearVariable](../-linear-variable/index.html) with two samples ranging from 0 to 1.



## Constructors


| | |
|---|---|
| [Flag](-flag.html) | [jvm]<br>open fun [Flag](-flag.html)(def: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))<br>the default value |


## Functions


| Name | Summary |
|---|---|
| [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-655675525%2FFunctions%2F-134779887) | [jvm]<br>open fun [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-655675525%2FFunctions%2F-134779887)(action: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |
| [getDefault](get-default.html) | [jvm]<br>open fun [getDefault](get-default.html)(): [Boolean](https://docs.oracle.com/javase/8/docs/api/java/lang/Boolean.html)<br>the default value for this [Variable](../-variable/index.html) |
| [iterator](../-variable/iterator.html) | [jvm]<br>open fun [iterator](../-variable/iterator.html)(): [Iterator](https://docs.oracle.com/javase/8/docs/api/java/util/Iterator.html)<[V](../-printable-variable/index.html)><br>abstract fun [iterator](../-arbitrary-variable/index.html#-1606146105%2FFunctions%2F-134779887)(): [Iterator](https://docs.oracle.com/javase/8/docs/api/java/util/Iterator.html)<[T](../../it.unibo.alchemist.loader.deployments/-deployment/get-associated-linking-rule.html)> |
| [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-677603448%2FFunctions%2F-134779887) | [jvm]<br>open fun [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-677603448%2FFunctions%2F-134779887)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[T](../../it.unibo.alchemist.loader.deployments/-deployment/get-associated-linking-rule.html)> |
| [steps](../-variable/steps.html) | [jvm]<br>open fun [steps](../-variable/steps.html)(): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)<br>the number of different values this [Variable](../-variable/index.html) may yield |
| [stream](stream.html) | [jvm]<br>open fun [stream](stream.html)(): [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html)<[Boolean](https://docs.oracle.com/javase/8/docs/api/java/lang/Boolean.html)><br>a view of the values of this variable as [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html). |
| [toString](../-printable-variable/to-string.html) | [jvm]<br>open fun [toString](../-printable-variable/to-string.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |

