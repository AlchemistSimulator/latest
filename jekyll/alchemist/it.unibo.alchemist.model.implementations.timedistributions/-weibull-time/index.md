---
title: WeibullTime
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.timedistributions](../index.html)/[WeibullTime](index.html)



# WeibullTime



[jvm]\
open class [WeibullTime](index.html)<[T](index.html)> : [AbstractDistribution](../-abstract-distribution/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)> 

Weibull distributed events.



## Parameters


jvm

| | |
|---|---|
| <T> | concentration type |



## Constructors


| | |
|---|---|
| [WeibullTime](-weibull-time.html) | [jvm]<br>open fun [WeibullTime](-weibull-time.html)(mean: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), deviation: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), random: RandomGenerator)<br>mean for this distribution |
| [WeibullTime](-weibull-time.html) | [jvm]<br>open fun [WeibullTime](-weibull-time.html)(mean: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), deviation: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), start: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html), random: RandomGenerator)<br>mean for this distribution |
| [WeibullTime](-weibull-time.html) | [jvm]<br>open fun [WeibullTime](-weibull-time.html)(shapeParameter: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), scaleParameter: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), offsetParameter: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), start: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html), random: RandomGenerator)<br>shape parameter for this distribution |


## Functions


| Name | Summary |
|---|---|
| [cloneOnNewNode](clone-on-new-node.html) | [jvm]<br>open fun [cloneOnNewNode](clone-on-new-node.html)(destination: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)>, currentTime: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html)): [WeibullTime](index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)><br>abstract fun [cloneOnNewNode](../../it.unibo.alchemist.model.interfaces/-time-distribution/clone-on-new-node.html)(p: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)>, p1: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html)): [TimeDistribution](../../it.unibo.alchemist.model.interfaces/-time-distribution/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)> |
| [getDeviation](get-deviation.html) | [jvm]<br>open fun [getDeviation](get-deviation.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>the standard deviation for this distribution. |
| [getMean](get-mean.html) | [jvm]<br>open fun [getMean](get-mean.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>the mean for this distribution. |
| [getNextOccurence](../-abstract-distribution/get-next-occurence.html) | [jvm]<br>fun [getNextOccurence](../-abstract-distribution/get-next-occurence.html)(): [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html)<br>abstract fun [getNextOccurence](../../it.unibo.alchemist.model.interfaces/-time-distribution/get-next-occurence.html)(): [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html) |
| [getRate](get-rate.html) | [jvm]<br>fun [getRate](get-rate.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [update](../-abstract-distribution/update.html) | [jvm]<br>fun [update](../-abstract-distribution/update.html)(currentTime: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html), hasBeenExecuted: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), additionalParameter: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>)<br>abstract fun [update](../../it.unibo.alchemist.model.interfaces/-time-distribution/update.html)(p: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html), p1: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), p2: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), p3: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |
| [updateStatus](update-status.html) | [jvm]<br>fun [updateStatus](update-status.html)(currentTime: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html), executed: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), param: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>)<br>Implement this method to update the distribution's internal status. |


## Inheritors


| Name |
|---|
| [WeibullDistributedWeibullTime](../-weibull-distributed-weibull-time/index.html) |

