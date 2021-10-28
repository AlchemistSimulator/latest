//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.timedistributions](../index.md)/[ExponentialTime](index.md)

# ExponentialTime

[jvm]\
open class [ExponentialTime](index.md)<[T](index.md)> : [AbstractDistribution](../-abstract-distribution/index.md)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-interact-with-others/index.md)> 

Markovian events.

## Parameters

jvm

| | |
|---|---|
| <T> | concentration type |

## Constructors

| | |
|---|---|
| [ExponentialTime](-exponential-time.md) | [jvm]<br>open fun [ExponentialTime](-exponential-time.md)(markovianRate: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), randomGenerator: RandomGenerator)<br>Markovian rate for this distribution |
| [ExponentialTime](-exponential-time.md) | [jvm]<br>open fun [ExponentialTime](-exponential-time.md)(markovianRate: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), start: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md), randomGenerator: RandomGenerator)<br>Markovian rate for this distribution |

## Functions

| Name | Summary |
|---|---|
| [cloneOnNewNode](clone-on-new-node.md) | [jvm]<br>open fun [cloneOnNewNode](clone-on-new-node.md)(destination: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-interact-with-others/index.md)>, currentTime: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md)): [ExponentialTime](index.md)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-interact-with-others/index.md)><br>Must be overridden by subclasses returning the correct instance.<br>[jvm]<br>abstract fun [cloneOnNewNode](../../it.unibo.alchemist.model.interfaces/-time-distribution/clone-on-new-node.md)(p: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-interact-with-others/index.md)>, p1: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md)): [TimeDistribution](../../it.unibo.alchemist.model.interfaces/-time-distribution/index.md)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-interact-with-others/index.md)> |
| [getNextOccurence](../-abstract-distribution/get-next-occurence.md) | [jvm]<br>fun [getNextOccurence](../-abstract-distribution/get-next-occurence.md)(): [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md)<br>abstract fun [getNextOccurence](../../it.unibo.alchemist.model.interfaces/-time-distribution/get-next-occurence.md)(): [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md) |
| [getRate](../../it.unibo.alchemist.model.interfaces/-time-distribution/get-rate.md) | [jvm]<br>abstract fun [getRate](../../it.unibo.alchemist.model.interfaces/-time-distribution/get-rate.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [update](../-abstract-distribution/update.md) | [jvm]<br>fun [update](../-abstract-distribution/update.md)(currentTime: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md), hasBeenExecuted: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), additionalParameter: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-interact-with-others/index.md), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>)<br>abstract fun [update](../../it.unibo.alchemist.model.interfaces/-time-distribution/update.md)(p: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md), p1: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), p2: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), p3: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-interact-with-others/index.md), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |
| [updateStatus](update-status.md) | [jvm]<br>fun [updateStatus](update-status.md)(currentTime: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md), executed: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), newpropensity: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-interact-with-others/index.md), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>)<br>Implement this method to update the distribution's internal status. |

## Properties

| Name | Summary |
|---|---|
| [rate](rate.md) | [jvm]<br>private val [rate](rate.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |

## Inheritors

| Name |
|---|
| [SAPEREExponentialTime](../-s-a-p-e-r-e-exponential-time/index.md) |
