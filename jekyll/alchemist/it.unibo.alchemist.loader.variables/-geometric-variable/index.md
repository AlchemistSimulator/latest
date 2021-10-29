---
title: GeometricVariable
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.loader.variables](../index.html)/[GeometricVariable](index.html)



# GeometricVariable



[jvm]\
class [GeometricVariable](index.html) : [PrintableVariable](../-printable-variable/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)> 

A variable ranging geometrically (exponentially) in a range. Ideal for log-scale comparisons. e.g. a [GeometricVariable](index.html) with minimum = 1, maximum = 100 and samples = 5 will range over [1, ~3.16, 10, ~31.62 100]. Both min and max must be strictly bigger than 0.



## Constructors


| | |
|---|---|
| [GeometricVariable](-geometric-variable.html) | [jvm]<br>open fun [GeometricVariable](-geometric-variable.html)(def: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), min: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), max: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), samples: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>default value |


## Functions


| Name | Summary |
|---|---|
| [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-655675525%2FFunctions%2F-134779887) | [jvm]<br>open fun [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-655675525%2FFunctions%2F-134779887)(action: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |
| [getDefault](get-default.html) | [jvm]<br>open fun [getDefault](get-default.html)(): [Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)<br>the default value for this [Variable](../-variable/index.html) |
| [iterator](../-variable/iterator.html) | [jvm]<br>open fun [iterator](../-variable/iterator.html)(): [Iterator](https://docs.oracle.com/javase/8/docs/api/java/util/Iterator.html)<[V](../-printable-variable/index.html)><br>abstract fun [iterator](../-arbitrary-variable/index.html#-1606146105%2FFunctions%2F-134779887)(): [Iterator](https://docs.oracle.com/javase/8/docs/api/java/util/Iterator.html)<[T](../../it.unibo.alchemist.loader.deployments/-deployment/get-associated-linking-rule.html)> |
| [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-677603448%2FFunctions%2F-134779887) | [jvm]<br>open fun [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-677603448%2FFunctions%2F-134779887)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[T](../../it.unibo.alchemist.loader.deployments/-deployment/get-associated-linking-rule.html)> |
| [steps](../-variable/steps.html) | [jvm]<br>open fun [steps](../-variable/steps.html)(): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)<br>the number of different values this [Variable](../-variable/index.html) may yield |
| [stream](stream.html) | [jvm]<br>open fun [stream](stream.html)(): [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)><br>a view of the values of this variable as [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html). |
| [toString](to-string.html) | [jvm]<br>open fun [toString](to-string.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |

