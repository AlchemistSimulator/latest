---
title: RandomDiracComb
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.timedistributions](../index.html)/[RandomDiracComb](index.html)



# RandomDiracComb



[jvm]\
open class [RandomDiracComb](index.html)<[T](index.html)> : [DiracComb](../-dirac-comb/index.html)<[T](../../it.unibo.alchemist/-supported-incarnations/get.html)> 

A [DiracComb](../-dirac-comb/index.html) whose rate is determined (uniformly) randomly within the provided bounds.



## Parameters


jvm

| | |
|---|---|
| <T> | concentration type |



## Constructors


| | |
|---|---|
| [RandomDiracComb](-random-dirac-comb.html) | [jvm]<br>open fun [RandomDiracComb](-random-dirac-comb.html)(rng: RandomGenerator, start: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html), minRate: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), maxRate: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>the RandomGenerator |
| [RandomDiracComb](-random-dirac-comb.html) | [jvm]<br>open fun [RandomDiracComb](-random-dirac-comb.html)(rng: RandomGenerator, minRate: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), maxRate: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>the RandomGenerator |


## Functions


| Name | Summary |
|---|---|
| [cloneOnNewNode](../-abstract-distribution/clone-on-new-node.html) | [jvm]<br>abstract fun [cloneOnNewNode](../-abstract-distribution/clone-on-new-node.html)(destination: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist/-supported-incarnations/get.html)>, currentTime: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html)): [AbstractDistribution](../-abstract-distribution/index.html)<[T](../../it.unibo.alchemist/-supported-incarnations/get.html)><br>fun [cloneOnNewNode](../-dirac-comb/clone-on-new-node.html)(destination: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist/-supported-incarnations/get.html)>, currentTime: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html)): [DiracComb](../-dirac-comb/index.html)<[T](../../it.unibo.alchemist/-supported-incarnations/get.html)><br>abstract fun [cloneOnNewNode](../../it.unibo.alchemist.model.interfaces/-time-distribution/clone-on-new-node.html)(p: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist/-supported-incarnations/get.html)>, p1: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html)): [TimeDistribution](../../it.unibo.alchemist.model.interfaces/-time-distribution/index.html)<[T](../../it.unibo.alchemist/-supported-incarnations/get.html)> |
| [getNextOccurence](../-abstract-distribution/get-next-occurence.html) | [jvm]<br>fun [getNextOccurence](../-abstract-distribution/get-next-occurence.html)(): [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html)<br>abstract fun [getNextOccurence](../../it.unibo.alchemist.model.interfaces/-time-distribution/get-next-occurence.html)(): [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html) |
| [getRate](../-dirac-comb/get-rate.html) | [jvm]<br>fun [getRate](../-dirac-comb/get-rate.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>abstract fun [getRate](../../it.unibo.alchemist.model.interfaces/-time-distribution/get-rate.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [toString](../-dirac-comb/to-string.html) | [jvm]<br>open fun [toString](../-dirac-comb/to-string.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |
| [update](../-abstract-distribution/update.html) | [jvm]<br>fun [update](../-abstract-distribution/update.html)(currentTime: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html), hasBeenExecuted: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), additionalParameter: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../../it.unibo.alchemist/-supported-incarnations/get.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>)<br>abstract fun [update](../../it.unibo.alchemist.model.interfaces/-time-distribution/update.html)(p: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html), p1: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), p2: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), p3: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../../it.unibo.alchemist/-supported-incarnations/get.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |

