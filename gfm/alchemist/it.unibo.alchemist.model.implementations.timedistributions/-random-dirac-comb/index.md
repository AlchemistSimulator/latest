//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.timedistributions](../index.md)/[RandomDiracComb](index.md)

# RandomDiracComb

[jvm]\
open class [RandomDiracComb](index.md)<[T](index.md)> : [DiracComb](../-dirac-comb/index.md)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.md)> 

A [DiracComb](../-dirac-comb/index.md) whose rate is determined (uniformly) randomly within the provided bounds.

## Parameters

jvm

| | |
|---|---|
| <T> | concentration type |

## Constructors

| | |
|---|---|
| [RandomDiracComb](-random-dirac-comb.md) | [jvm]<br>open fun [RandomDiracComb](-random-dirac-comb.md)(rng: RandomGenerator, start: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md), minRate: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), maxRate: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>the RandomGenerator |
| [RandomDiracComb](-random-dirac-comb.md) | [jvm]<br>open fun [RandomDiracComb](-random-dirac-comb.md)(rng: RandomGenerator, minRate: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), maxRate: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>the RandomGenerator |

## Functions

| Name | Summary |
|---|---|
| [cloneOnNewNode](../-abstract-distribution/clone-on-new-node.md) | [jvm]<br>abstract fun [cloneOnNewNode](../-abstract-distribution/clone-on-new-node.md)(destination: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.md)>, currentTime: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md)): [AbstractDistribution](../-abstract-distribution/index.md)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.md)><br>fun [cloneOnNewNode](../-dirac-comb/clone-on-new-node.md)(destination: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.md)>, currentTime: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md)): [DiracComb](../-dirac-comb/index.md)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.md)><br>abstract fun [cloneOnNewNode](../../it.unibo.alchemist.model.interfaces/-time-distribution/clone-on-new-node.md)(p: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.md)>, p1: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md)): [TimeDistribution](../../it.unibo.alchemist.model.interfaces/-time-distribution/index.md)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.md)> |
| [getNextOccurence](../-abstract-distribution/get-next-occurence.md) | [jvm]<br>fun [getNextOccurence](../-abstract-distribution/get-next-occurence.md)(): [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md)<br>abstract fun [getNextOccurence](../../it.unibo.alchemist.model.interfaces/-time-distribution/get-next-occurence.md)(): [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md) |
| [getRate](../-dirac-comb/get-rate.md) | [jvm]<br>fun [getRate](../-dirac-comb/get-rate.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>abstract fun [getRate](../../it.unibo.alchemist.model.interfaces/-time-distribution/get-rate.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [toString](../-dirac-comb/to-string.md) | [jvm]<br>open fun [toString](../-dirac-comb/to-string.md)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |
| [update](../-abstract-distribution/update.md) | [jvm]<br>fun [update](../-abstract-distribution/update.md)(currentTime: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md), hasBeenExecuted: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), additionalParameter: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.md), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>)<br>abstract fun [update](../../it.unibo.alchemist.model.interfaces/-time-distribution/update.md)(p: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md), p1: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), p2: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), p3: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.md), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |
