---
title: createTimeDistribution
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces](../index.html)/[Incarnation](index.html)/[createTimeDistribution](create-time-distribution.html)



# createTimeDistribution



[jvm]\
abstract fun [createTimeDistribution](create-time-distribution.html)(randomGenerator: RandomGenerator, environment: [Environment](../-environment/index.html)<[T](../-node/index.html), [P](../-position2-d/index.html)>, node: [Node](../-node/index.html)<[T](../-node/index.html)>, @Nullable()parameter: @Nullable()[String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [TimeDistribution](../-time-distribution/index.html)<[T](../-node/index.html)>



#### Return



a new [TimeDistribution](../-time-distribution/index.html)



## Parameters


jvm

| | |
|---|---|
| randomGenerator | the random engine |
| environment | the environment that will host this object |
| node | the node that will host this object |
| parameter | a [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) describing the object |




