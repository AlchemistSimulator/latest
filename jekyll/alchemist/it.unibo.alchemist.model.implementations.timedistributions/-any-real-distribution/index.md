---
title: AnyRealDistribution
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.timedistributions](../index.html)/[AnyRealDistribution](index.html)



# AnyRealDistribution



[jvm]\
open class [AnyRealDistribution](index.html)<[T](index.html)> : [AbstractDistribution](../-abstract-distribution/index.html)<[T](../../it.unibo.alchemist/-supported-incarnations/get.html)> 

This class is able to use any distribution provided by Apache Math 3 as a subclass of RealDistribution, blocking the execution if [getPropensityContribution](../../it.unibo.alchemist.model.interfaces/-condition/get-propensity-contribution.html) returns zero for any condition.



## Parameters


jvm

| | |
|---|---|
| <T> | concentration type |



## Constructors


| | |
|---|---|
| [AnyRealDistribution](-any-real-distribution.html) | [jvm]<br>open fun [AnyRealDistribution](-any-real-distribution.html)(rng: RandomGenerator, distribution: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), parameters: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)>)<br>the RandomGenerator |
| [AnyRealDistribution](-any-real-distribution.html) | [jvm]<br>open fun [AnyRealDistribution](-any-real-distribution.html)(start: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html), rng: RandomGenerator, distribution: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), parameters: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)>)<br>the initial time |
| [AnyRealDistribution](-any-real-distribution.html) | [jvm]<br>open fun [AnyRealDistribution](-any-real-distribution.html)(distribution: RealDistribution)<br>the [AnyRealDistribution](index.html) to use. |
| [AnyRealDistribution](-any-real-distribution.html) | [jvm]<br>open fun [AnyRealDistribution](-any-real-distribution.html)(start: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html), distribution: RealDistribution)<br>distribution start time |


## Functions


| Name | Summary |
|---|---|
| [cloneOnNewNode](clone-on-new-node.html) | [jvm]<br>open fun [cloneOnNewNode](clone-on-new-node.html)(destination: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist/-supported-incarnations/get.html)>, currentTime: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html)): [AbstractDistribution](../-abstract-distribution/index.html)<[T](../../it.unibo.alchemist/-supported-incarnations/get.html)><br>abstract fun [cloneOnNewNode](../../it.unibo.alchemist.model.interfaces/-time-distribution/clone-on-new-node.html)(p: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist/-supported-incarnations/get.html)>, p1: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html)): [TimeDistribution](../../it.unibo.alchemist.model.interfaces/-time-distribution/index.html)<[T](../../it.unibo.alchemist/-supported-incarnations/get.html)> |
| [getNextOccurence](../-abstract-distribution/get-next-occurence.html) | [jvm]<br>fun [getNextOccurence](../-abstract-distribution/get-next-occurence.html)(): [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html)<br>abstract fun [getNextOccurence](../../it.unibo.alchemist.model.interfaces/-time-distribution/get-next-occurence.html)(): [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html) |
| [getRate](get-rate.html) | [jvm]<br>fun [getRate](get-rate.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [update](../-abstract-distribution/update.html) | [jvm]<br>fun [update](../-abstract-distribution/update.html)(currentTime: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html), hasBeenExecuted: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), additionalParameter: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../../it.unibo.alchemist/-supported-incarnations/get.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>)<br>abstract fun [update](../../it.unibo.alchemist.model.interfaces/-time-distribution/update.html)(p: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html), p1: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), p2: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), p3: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../../it.unibo.alchemist/-supported-incarnations/get.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |


## Inheritors


| Name |
|---|
| [MoleculeControlledTimeDistribution](../-molecule-controlled-time-distribution/index.html) |

