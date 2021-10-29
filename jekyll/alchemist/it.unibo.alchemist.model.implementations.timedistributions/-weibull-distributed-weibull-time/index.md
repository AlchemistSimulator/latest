---
title: WeibullDistributedWeibullTime
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.timedistributions](../index.html)/[WeibullDistributedWeibullTime](index.html)



# WeibullDistributedWeibullTime



[jvm]\
open class [WeibullDistributedWeibullTime](index.html)<[T](index.html)> : [WeibullTime](../-weibull-time/index.html)<[T](../../it.unibo.alchemist/-supported-incarnations/get.html)> 

Weibull distributed events, with different (Weibull distributed) mean.



## Parameters


jvm

| | |
|---|---|
| <T> | concentration type |



## Constructors


| | |
|---|---|
| [WeibullDistributedWeibullTime](-weibull-distributed-weibull-time.html) | [jvm]<br>open fun [WeibullDistributedWeibullTime](-weibull-distributed-weibull-time.html)(mean: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), deviceDeviation: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), networkDeviation: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), random: RandomGenerator)<br>mean time interval across the network |
| [WeibullDistributedWeibullTime](-weibull-distributed-weibull-time.html) | [jvm]<br>open fun [WeibullDistributedWeibullTime](-weibull-distributed-weibull-time.html)(mean: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), deviceDeviation: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), networkDeviation: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), start: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html), random: RandomGenerator)<br>mean time interval across the network |
| [WeibullDistributedWeibullTime](-weibull-distributed-weibull-time.html) | [jvm]<br>open fun [WeibullDistributedWeibullTime](-weibull-distributed-weibull-time.html)(mean: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), deviceDeviation: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), networkDeviation: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), deviationDeviation: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), start: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html), random: RandomGenerator)<br>mean time interval across the network |


## Functions


| Name | Summary |
|---|---|
| [cloneOnNewNode](../-abstract-distribution/clone-on-new-node.html) | [jvm]<br>abstract fun [cloneOnNewNode](../-abstract-distribution/clone-on-new-node.html)(destination: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist/-supported-incarnations/get.html)>, currentTime: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html)): [AbstractDistribution](../-abstract-distribution/index.html)<[T](../../it.unibo.alchemist/-supported-incarnations/get.html)><br>open fun [cloneOnNewNode](../-weibull-time/clone-on-new-node.html)(destination: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist/-supported-incarnations/get.html)>, currentTime: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html)): [WeibullTime](../-weibull-time/index.html)<[T](../../it.unibo.alchemist/-supported-incarnations/get.html)><br>abstract fun [cloneOnNewNode](../../it.unibo.alchemist.model.interfaces/-time-distribution/clone-on-new-node.html)(p: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist/-supported-incarnations/get.html)>, p1: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html)): [TimeDistribution](../../it.unibo.alchemist.model.interfaces/-time-distribution/index.html)<[T](../../it.unibo.alchemist/-supported-incarnations/get.html)> |
| [getDeviation](../-weibull-time/get-deviation.html) | [jvm]<br>open fun [getDeviation](../-weibull-time/get-deviation.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>the standard deviation for this distribution. |
| [getMean](../-weibull-time/get-mean.html) | [jvm]<br>open fun [getMean](../-weibull-time/get-mean.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>the mean for this distribution. |
| [getNextOccurence](../-abstract-distribution/get-next-occurence.html) | [jvm]<br>fun [getNextOccurence](../-abstract-distribution/get-next-occurence.html)(): [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html)<br>abstract fun [getNextOccurence](../../it.unibo.alchemist.model.interfaces/-time-distribution/get-next-occurence.html)(): [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html) |
| [getRate](../-weibull-time/get-rate.html) | [jvm]<br>fun [getRate](../-weibull-time/get-rate.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>abstract fun [getRate](../../it.unibo.alchemist.model.interfaces/-time-distribution/get-rate.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [update](../-abstract-distribution/update.html) | [jvm]<br>fun [update](../-abstract-distribution/update.html)(currentTime: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html), hasBeenExecuted: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), additionalParameter: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../../it.unibo.alchemist/-supported-incarnations/get.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>)<br>abstract fun [update](../../it.unibo.alchemist.model.interfaces/-time-distribution/update.html)(p: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html), p1: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), p2: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), p3: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../../it.unibo.alchemist/-supported-incarnations/get.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |
| [updateStatus](../-weibull-time/update-status.html) | [jvm]<br>fun [updateStatus](../-weibull-time/update-status.html)(currentTime: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html), executed: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), param: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../../it.unibo.alchemist/-supported-incarnations/get.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>)<br>Implement this method to update the distribution's internal status. |

