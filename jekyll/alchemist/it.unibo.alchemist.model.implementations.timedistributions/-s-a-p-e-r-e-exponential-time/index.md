---
title: SAPEREExponentialTime
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.timedistributions](../index.html)/[SAPEREExponentialTime](index.html)



# SAPEREExponentialTime



[jvm]\
class [SAPEREExponentialTime](index.html) : [ExponentialTime](../-exponential-time/index.html)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html)>> , [SAPERETimeDistribution](../-s-a-p-e-r-e-time-distribution/index.html)

Allows for a Markovian event whose lambda is computed dynamically using a rate equation.



## Constructors


| | |
|---|---|
| [SAPEREExponentialTime](-s-a-p-e-r-e-exponential-time.html) | [jvm]<br>open fun [SAPEREExponentialTime](-s-a-p-e-r-e-exponential-time.html)(rateEquation: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), random: RandomGenerator)<br>the rate equation |
| [SAPEREExponentialTime](-s-a-p-e-r-e-exponential-time.html) | [jvm]<br>open fun [SAPEREExponentialTime](-s-a-p-e-r-e-exponential-time.html)(rateEquation: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), start: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html), random: RandomGenerator)<br>the rate equation |


## Functions


| Name | Summary |
|---|---|
| [cloneOnNewNode](../-abstract-distribution/clone-on-new-node.html) | [jvm]<br>abstract fun [cloneOnNewNode](../-abstract-distribution/clone-on-new-node.html)(p: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.actions/-abstract-action/index.html)>, p1: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html)): [AbstractDistribution](../-abstract-distribution/index.html)<[T](../../it.unibo.alchemist.model.implementations.actions/-abstract-action/index.html)><br>open fun [cloneOnNewNode](../-exponential-time/clone-on-new-node.html)(destination: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.actions/-abstract-action/index.html)>, currentTime: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html)): [ExponentialTime](../-exponential-time/index.html)<[T](../../it.unibo.alchemist.model.implementations.actions/-abstract-action/index.html)><br>abstract fun [cloneOnNewNode](../../it.unibo.alchemist.model.interfaces/-time-distribution/clone-on-new-node.html)(p: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.actions/-abstract-action/index.html)>, p1: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html)): [TimeDistribution](../../it.unibo.alchemist.model.interfaces/-time-distribution/index.html)<[T](../../it.unibo.alchemist.model.implementations.actions/-abstract-action/index.html)> |
| [getNextOccurence](../-abstract-distribution/get-next-occurence.html) | [jvm]<br>fun [getNextOccurence](../-abstract-distribution/get-next-occurence.html)(): [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html) |
| [getRate](get-rate.html) | [jvm]<br>open fun [getRate](get-rate.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getRateEquation](get-rate-equation.html) | [jvm]<br>open fun [getRateEquation](get-rate-equation.html)(): [IExpression](../../it.unibo.alchemist.expressions.interfaces/-i-expression/index.html)<br>the rate equation |
| [isStatic](is-static.html) | [jvm]<br>open fun [isStatic](is-static.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>true if the equation is actually a number |
| [setMatches](../-s-a-p-e-r-e-time-distribution/set-matches.html) | [jvm]<br>abstract fun [setMatches](../-s-a-p-e-r-e-time-distribution/set-matches.html)(match: [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<HashString, [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>>)<br>the map of matches |
| [update](../-abstract-distribution/update.html) | [jvm]<br>fun [update](../-abstract-distribution/update.html)(currentTime: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html), hasBeenExecuted: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), additionalParameter: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../../it.unibo.alchemist.model.implementations.actions/-abstract-action/index.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |
| [updateStatus](../-exponential-time/update-status.html) | [jvm]<br>fun [updateStatus](../-exponential-time/update-status.html)(currentTime: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html), executed: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), newpropensity: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../../it.unibo.alchemist.model.implementations.actions/-abstract-action/index.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |


## Properties


| Name | Summary |
|---|---|
| [matches](matches.html) | [jvm]<br>private open var [matches](matches.html): [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<HashString, [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>> |

