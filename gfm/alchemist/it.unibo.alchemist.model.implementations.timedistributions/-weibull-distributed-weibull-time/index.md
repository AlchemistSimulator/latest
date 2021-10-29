//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.timedistributions](../index.md)/[WeibullDistributedWeibullTime](index.md)

# WeibullDistributedWeibullTime

[jvm]\
open class [WeibullDistributedWeibullTime](index.md)<[T](index.md)> : [WeibullTime](../-weibull-time/index.md)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.md)> 

Weibull distributed events, with different (Weibull distributed) mean.

## Parameters

jvm

| | |
|---|---|
| <T> | concentration type |

## Constructors

| | |
|---|---|
| [WeibullDistributedWeibullTime](-weibull-distributed-weibull-time.md) | [jvm]<br>open fun [WeibullDistributedWeibullTime](-weibull-distributed-weibull-time.md)(mean: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), deviceDeviation: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), networkDeviation: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), random: RandomGenerator)<br>mean time interval across the network |
| [WeibullDistributedWeibullTime](-weibull-distributed-weibull-time.md) | [jvm]<br>open fun [WeibullDistributedWeibullTime](-weibull-distributed-weibull-time.md)(mean: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), deviceDeviation: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), networkDeviation: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), start: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md), random: RandomGenerator)<br>mean time interval across the network |
| [WeibullDistributedWeibullTime](-weibull-distributed-weibull-time.md) | [jvm]<br>open fun [WeibullDistributedWeibullTime](-weibull-distributed-weibull-time.md)(mean: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), deviceDeviation: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), networkDeviation: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), deviationDeviation: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), start: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md), random: RandomGenerator)<br>mean time interval across the network |

## Functions

| Name | Summary |
|---|---|
| [cloneOnNewNode](../-abstract-distribution/clone-on-new-node.md) | [jvm]<br>abstract fun [cloneOnNewNode](../-abstract-distribution/clone-on-new-node.md)(destination: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.md)>, currentTime: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md)): [AbstractDistribution](../-abstract-distribution/index.md)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.md)><br>open fun [cloneOnNewNode](../-weibull-time/clone-on-new-node.md)(destination: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.md)>, currentTime: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md)): [WeibullTime](../-weibull-time/index.md)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.md)><br>abstract fun [cloneOnNewNode](../../it.unibo.alchemist.model.interfaces/-time-distribution/clone-on-new-node.md)(p: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.md)>, p1: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md)): [TimeDistribution](../../it.unibo.alchemist.model.interfaces/-time-distribution/index.md)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.md)> |
| [getDeviation](../-weibull-time/get-deviation.md) | [jvm]<br>open fun [getDeviation](../-weibull-time/get-deviation.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>the standard deviation for this distribution. |
| [getMean](../-weibull-time/get-mean.md) | [jvm]<br>open fun [getMean](../-weibull-time/get-mean.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>the mean for this distribution. |
| [getNextOccurence](../-abstract-distribution/get-next-occurence.md) | [jvm]<br>fun [getNextOccurence](../-abstract-distribution/get-next-occurence.md)(): [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md)<br>abstract fun [getNextOccurence](../../it.unibo.alchemist.model.interfaces/-time-distribution/get-next-occurence.md)(): [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md) |
| [getRate](../-weibull-time/get-rate.md) | [jvm]<br>fun [getRate](../-weibull-time/get-rate.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>abstract fun [getRate](../../it.unibo.alchemist.model.interfaces/-time-distribution/get-rate.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [update](../-abstract-distribution/update.md) | [jvm]<br>fun [update](../-abstract-distribution/update.md)(currentTime: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md), hasBeenExecuted: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), additionalParameter: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.md), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>)<br>abstract fun [update](../../it.unibo.alchemist.model.interfaces/-time-distribution/update.md)(p: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md), p1: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), p2: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), p3: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.md), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |
| [updateStatus](../-weibull-time/update-status.md) | [jvm]<br>fun [updateStatus](../-weibull-time/update-status.md)(currentTime: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md), executed: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), param: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.md), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>)<br>Implement this method to update the distribution's internal status. |
