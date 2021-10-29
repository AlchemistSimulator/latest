---
title: SAPERETimeDistribution
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.timedistributions](../index.html)/[SAPERETimeDistribution](index.html)



# SAPERETimeDistribution



[jvm]\
interface [SAPERETimeDistribution](index.html) : [TimeDistribution](../../it.unibo.alchemist.model.interfaces/-time-distribution/index.html)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html)>> 

Interface for TimeDistribution that need matches.



## Functions


| Name | Summary |
|---|---|
| [cloneOnNewNode](../../it.unibo.alchemist.model.interfaces/-time-distribution/clone-on-new-node.html) | [jvm]<br>abstract fun [cloneOnNewNode](../../it.unibo.alchemist.model.interfaces/-time-distribution/clone-on-new-node.html)(p: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.conditions/-abstract-condition/index.html)>, p1: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html)): [TimeDistribution](../../it.unibo.alchemist.model.interfaces/-time-distribution/index.html)<[T](../../it.unibo.alchemist.model.implementations.conditions/-abstract-condition/index.html)> |
| [getNextOccurence](../../it.unibo.alchemist.model.interfaces/-time-distribution/get-next-occurence.html) | [jvm]<br>abstract fun [getNextOccurence](../../it.unibo.alchemist.model.interfaces/-time-distribution/get-next-occurence.html)(): [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html) |
| [getRate](../../it.unibo.alchemist.model.interfaces/-time-distribution/get-rate.html) | [jvm]<br>abstract fun [getRate](../../it.unibo.alchemist.model.interfaces/-time-distribution/get-rate.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getRateEquation](get-rate-equation.html) | [jvm]<br>abstract fun [getRateEquation](get-rate-equation.html)(): [IExpression](../../it.unibo.alchemist.expressions.interfaces/-i-expression/index.html)<br>the rate equation |
| [isStatic](is-static.html) | [jvm]<br>abstract fun [isStatic](is-static.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>true if the equation is actually a number |
| [setMatches](set-matches.html) | [jvm]<br>abstract fun [setMatches](set-matches.html)(match: [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<HashString, [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>>)<br>the map of matches |
| [update](../../it.unibo.alchemist.model.interfaces/-time-distribution/update.html) | [jvm]<br>abstract fun [update](../../it.unibo.alchemist.model.interfaces/-time-distribution/update.html)(p: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html), p1: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), p2: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), p3: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../../it.unibo.alchemist.model.implementations.conditions/-abstract-condition/index.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |


## Inheritors


| Name |
|---|
| [SAPEREExponentialTime](../-s-a-p-e-r-e-exponential-time/index.html) |

