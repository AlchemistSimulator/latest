//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.timedistributions](../index.md)/[WeibullDistributedWeibullTime](index.md)/[WeibullDistributedWeibullTime](-weibull-distributed-weibull-time.md)

# WeibullDistributedWeibullTime

[jvm]\
open fun [WeibullDistributedWeibullTime](-weibull-distributed-weibull-time.md)(mean: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), deviceDeviation: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), networkDeviation: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), random: RandomGenerator)

## Parameters

jvm

| | |
|---|---|
| mean | mean time interval across the network |
| deviceDeviation | standard deviation of time intervals in each device |
| networkDeviation | standard deviation of time intervals across devices |
| random | RandomGenerator used internally |

[jvm]\
open fun [WeibullDistributedWeibullTime](-weibull-distributed-weibull-time.md)(mean: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), deviceDeviation: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), networkDeviation: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), start: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md), random: RandomGenerator)

## Parameters

jvm

| | |
|---|---|
| mean | mean time interval across the network |
| deviceDeviation | standard deviation of time intervals in each device |
| networkDeviation | standard deviation of time intervals across devices |
| start | initial time |
| random | RandomGenerator used internally |

[jvm]\
open fun [WeibullDistributedWeibullTime](-weibull-distributed-weibull-time.md)(mean: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), deviceDeviation: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), networkDeviation: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), deviationDeviation: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), start: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md), random: RandomGenerator)

## Parameters

jvm

| | |
|---|---|
| mean | mean time interval across the network |
| deviceDeviation | standard deviation of time intervals in each device |
| networkDeviation | standard deviation of time intervals across devices |
| deviationDeviation | standard deviation of standard deviations across devices |
| start | initial time |
| random | RandomGenerator used internally |
