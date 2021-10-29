//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.timedistributions](../index.md)/[DiracComb](index.md)

# DiracComb

[jvm]\
open class [DiracComb](index.md)<[T](index.md)> : [AbstractDistribution](../-abstract-distribution/index.md)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.md)> 

A DiracComb is a sequence of events that happen every fixed time interval.

## Parameters

jvm

| | |
|---|---|
| <T> | concentration type |

## Constructors

| | |
|---|---|
| [DiracComb](-dirac-comb.md) | [jvm]<br>open fun [DiracComb](-dirac-comb.md)(start: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md), rate: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>initial time |
| [DiracComb](-dirac-comb.md) | [jvm]<br>open fun [DiracComb](-dirac-comb.md)(rate: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>how many events should happen per time unit |

## Functions

| Name | Summary |
|---|---|
| [cloneOnNewNode](clone-on-new-node.md) | [jvm]<br>fun [cloneOnNewNode](clone-on-new-node.md)(destination: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.md)>, currentTime: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md)): [DiracComb](index.md)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.md)><br>abstract fun [cloneOnNewNode](../../it.unibo.alchemist.model.interfaces/-time-distribution/clone-on-new-node.md)(p: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.md)>, p1: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md)): [TimeDistribution](../../it.unibo.alchemist.model.interfaces/-time-distribution/index.md)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.md)> |
| [getNextOccurence](../-abstract-distribution/get-next-occurence.md) | [jvm]<br>fun [getNextOccurence](../-abstract-distribution/get-next-occurence.md)(): [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md)<br>abstract fun [getNextOccurence](../../it.unibo.alchemist.model.interfaces/-time-distribution/get-next-occurence.md)(): [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md) |
| [getRate](get-rate.md) | [jvm]<br>fun [getRate](get-rate.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [toString](to-string.md) | [jvm]<br>open fun [toString](to-string.md)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |
| [update](../-abstract-distribution/update.md) | [jvm]<br>fun [update](../-abstract-distribution/update.md)(currentTime: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md), hasBeenExecuted: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), additionalParameter: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.md), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>)<br>abstract fun [update](../../it.unibo.alchemist.model.interfaces/-time-distribution/update.md)(p: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md), p1: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), p2: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), p3: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.md), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |

## Inheritors

| Name |
|---|
| [RandomDiracComb](../-random-dirac-comb/index.md) |
