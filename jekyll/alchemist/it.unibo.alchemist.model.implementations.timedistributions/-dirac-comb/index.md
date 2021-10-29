---
title: DiracComb
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.timedistributions](../index.html)/[DiracComb](index.html)



# DiracComb



[jvm]\
open class [DiracComb](index.html)<[T](index.html)> : [AbstractDistribution](../-abstract-distribution/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)> 

A DiracComb is a sequence of events that happen every fixed time interval.



## Parameters


jvm

| | |
|---|---|
| <T> | concentration type |



## Constructors


| | |
|---|---|
| [DiracComb](-dirac-comb.html) | [jvm]<br>open fun [DiracComb](-dirac-comb.html)(start: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html), rate: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>initial time |
| [DiracComb](-dirac-comb.html) | [jvm]<br>open fun [DiracComb](-dirac-comb.html)(rate: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>how many events should happen per time unit |


## Functions


| Name | Summary |
|---|---|
| [cloneOnNewNode](clone-on-new-node.html) | [jvm]<br>fun [cloneOnNewNode](clone-on-new-node.html)(destination: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)>, currentTime: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html)): [DiracComb](index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)><br>abstract fun [cloneOnNewNode](../../it.unibo.alchemist.model.interfaces/-time-distribution/clone-on-new-node.html)(p: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)>, p1: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html)): [TimeDistribution](../../it.unibo.alchemist.model.interfaces/-time-distribution/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)> |
| [getNextOccurence](../-abstract-distribution/get-next-occurence.html) | [jvm]<br>fun [getNextOccurence](../-abstract-distribution/get-next-occurence.html)(): [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html)<br>abstract fun [getNextOccurence](../../it.unibo.alchemist.model.interfaces/-time-distribution/get-next-occurence.html)(): [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html) |
| [getRate](get-rate.html) | [jvm]<br>fun [getRate](get-rate.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [toString](to-string.html) | [jvm]<br>open fun [toString](to-string.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |
| [update](../-abstract-distribution/update.html) | [jvm]<br>fun [update](../-abstract-distribution/update.html)(currentTime: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html), hasBeenExecuted: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), additionalParameter: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>)<br>abstract fun [update](../../it.unibo.alchemist.model.interfaces/-time-distribution/update.html)(p: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html), p1: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), p2: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), p3: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |


## Inheritors


| Name |
|---|
| [RandomDiracComb](../-random-dirac-comb/index.html) |

