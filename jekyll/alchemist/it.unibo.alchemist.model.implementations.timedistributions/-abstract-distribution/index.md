---
title: AbstractDistribution
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.timedistributions](../index.html)/[AbstractDistribution](index.html)



# AbstractDistribution



[jvm]\
abstract class [AbstractDistribution](index.html)<[T](index.html)> : [TimeDistribution](../../it.unibo.alchemist.model.interfaces/-time-distribution/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html)> 

This class provides, through a template method pattern, an utility that ensures that the distribution does not trigger events before its initial scheduling time.



## Parameters


jvm

| | |
|---|---|
| <T> | concentration type |



## Constructors


| | |
|---|---|
| [AbstractDistribution](-abstract-distribution.html) | [jvm]<br>open fun [AbstractDistribution](-abstract-distribution.html)(start: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html))<br>initial time |


## Functions


| Name | Summary |
|---|---|
| [cloneOnNewNode](clone-on-new-node.html) | [jvm]<br>abstract fun [cloneOnNewNode](clone-on-new-node.html)(destination: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html)>, currentTime: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html)): [AbstractDistribution](index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html)> |
| [getNextOccurence](get-next-occurence.html) | [jvm]<br>fun [getNextOccurence](get-next-occurence.html)(): [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html) |
| [getRate](../../it.unibo.alchemist.model.interfaces/-time-distribution/get-rate.html) | [jvm]<br>abstract fun [getRate](../../it.unibo.alchemist.model.interfaces/-time-distribution/get-rate.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [update](update.html) | [jvm]<br>fun [update](update.html)(currentTime: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html), hasBeenExecuted: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), additionalParameter: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |


## Inheritors


| Name |
|---|
| [WeibullTime](../-weibull-time/index.html) |
| [DiracComb](../-dirac-comb/index.html) |
| [Trigger](../-trigger/index.html) |
| [ExponentialTime](../-exponential-time/index.html) |
| [AnyRealDistribution](../-any-real-distribution/index.html) |

