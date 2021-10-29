---
title: TimeDistribution
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces](../index.html)/[TimeDistribution](index.html)



# TimeDistribution



[jvm]\
interface [TimeDistribution](index.html)<[T](index.html)> : [Cloneable](https://docs.oracle.com/javase/8/docs/api/java/lang/Cloneable.html), [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)

This interface represents a temporal distribution for any event.



## Parameters


jvm

| | |
|---|---|
| <T> | concentration type |



## Functions


| Name | Summary |
|---|---|
| [cloneOnNewNode](clone-on-new-node.html) | [jvm]<br>abstract fun [cloneOnNewNode](clone-on-new-node.html)(destination: [Node](../-node/index.html)<[T](../../it.unibo.alchemist.core.interfaces/-scheduler/index.html)>, currentTime: [Time](../-time/index.html)): [TimeDistribution](index.html)<[T](../../it.unibo.alchemist.core.interfaces/-scheduler/index.html)><br>the node where the newly created time distribution will be placed |
| [getNextOccurence](get-next-occurence.html) | [jvm]<br>abstract fun [getNextOccurence](get-next-occurence.html)(): [Time](../-time/index.html)<br>the next time at which the event will occur |
| [getRate](get-rate.html) | [jvm]<br>abstract fun [getRate](get-rate.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>how many times per time unit the event will happen on average |
| [update](update.html) | [jvm]<br>abstract fun [update](update.html)(currentTime: [Time](../-time/index.html), executed: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), param: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), environment: [Environment](../-environment/index.html)<[T](../../it.unibo.alchemist.core.interfaces/-scheduler/index.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>)<br>Updates the internal status. |


## Inheritors


| Name |
|---|
| [AbstractDistribution](../../it.unibo.alchemist.model.implementations.timedistributions/-abstract-distribution/index.html) |
| [SAPERETimeDistribution](../../it.unibo.alchemist.model.implementations.timedistributions/-s-a-p-e-r-e-time-distribution/index.html) |

