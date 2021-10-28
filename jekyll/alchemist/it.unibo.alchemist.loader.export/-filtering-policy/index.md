---
title: FilteringPolicy
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.loader.export](../index.html)/[FilteringPolicy](index.html)



# FilteringPolicy



[jvm]\
@[FunctionalInterface](https://docs.oracle.com/javase/8/docs/api/java/lang/FunctionalInterface.html)()



interface [FilteringPolicy](index.html) : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)

Expresses a flat map operation over a double.



## Functions


| Name | Summary |
|---|---|
| [apply](apply.html) | [jvm]<br>abstract fun [apply](apply.html)(value: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [DoubleStream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/DoubleStream.html)<br>From a single value, builds a stream of values. |

