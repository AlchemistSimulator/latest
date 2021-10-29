//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.timedistributions](../index.md)/[AbstractDistribution](index.md)

# AbstractDistribution

[jvm]\
abstract class [AbstractDistribution](index.md)<[T](index.md)> : [TimeDistribution](../../it.unibo.alchemist.model.interfaces/-time-distribution/index.md)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.md)> 

This class provides, through a template method pattern, an utility that ensures that the distribution does not trigger events before its initial scheduling time.

## Parameters

jvm

| | |
|---|---|
| <T> | concentration type |

## Constructors

| | |
|---|---|
| [AbstractDistribution](-abstract-distribution.md) | [jvm]<br>open fun [AbstractDistribution](-abstract-distribution.md)(start: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md))<br>initial time |

## Functions

| Name | Summary |
|---|---|
| [cloneOnNewNode](clone-on-new-node.md) | [jvm]<br>abstract fun [cloneOnNewNode](clone-on-new-node.md)(destination: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.md)>, currentTime: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md)): [AbstractDistribution](index.md)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.md)> |
| [getNextOccurence](get-next-occurence.md) | [jvm]<br>fun [getNextOccurence](get-next-occurence.md)(): [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md) |
| [getRate](../../it.unibo.alchemist.model.interfaces/-time-distribution/get-rate.md) | [jvm]<br>abstract fun [getRate](../../it.unibo.alchemist.model.interfaces/-time-distribution/get-rate.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [update](update.md) | [jvm]<br>fun [update](update.md)(currentTime: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md), hasBeenExecuted: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), additionalParameter: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.md), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |

## Inheritors

| Name |
|---|
| [WeibullTime](../-weibull-time/index.md) |
| [DiracComb](../-dirac-comb/index.md) |
| [Trigger](../-trigger/index.md) |
| [ExponentialTime](../-exponential-time/index.md) |
| [AnyRealDistribution](../-any-real-distribution/index.md) |
