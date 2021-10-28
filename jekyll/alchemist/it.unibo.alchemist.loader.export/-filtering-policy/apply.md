---
title: apply
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.loader.export](../index.html)/[FilteringPolicy](index.html)/[apply](apply.html)



# apply



[jvm]\
abstract fun [apply](apply.html)(value: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [DoubleStream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/DoubleStream.html)



From a single value, builds a stream of values.



#### Return



a stream of double values. In most cases, it will be a [DoubleStream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/DoubleStream.html) of a single value, but may easily be an empty [DoubleStream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/DoubleStream.html) (in case the value must be filtered). Also, the case in which a single value gets mapped onto multiple values is supported by this interface.



## Parameters


jvm

| | |
|---|---|
| value | the input value |




