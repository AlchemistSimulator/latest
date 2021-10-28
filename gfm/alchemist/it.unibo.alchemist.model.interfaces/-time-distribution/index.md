//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces](../index.md)/[TimeDistribution](index.md)

# TimeDistribution

[jvm]\
interface [TimeDistribution](index.md)<[T](index.md)> : [Cloneable](https://docs.oracle.com/javase/8/docs/api/java/lang/Cloneable.html), [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)

This interface represents a temporal distribution for any event.

## Parameters

jvm

| | |
|---|---|
| <T> | concentration type |

## Functions

| Name | Summary |
|---|---|
| [cloneOnNewNode](clone-on-new-node.md) | [jvm]<br>abstract fun [cloneOnNewNode](clone-on-new-node.md)(destination: [Node](../-node/index.md)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.md)>, currentTime: [Time](../-time/index.md)): [TimeDistribution](index.md)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.md)><br>the node where the newly created time distribution will be placed |
| [getNextOccurence](get-next-occurence.md) | [jvm]<br>abstract fun [getNextOccurence](get-next-occurence.md)(): [Time](../-time/index.md)<br>the next time at which the event will occur |
| [getRate](get-rate.md) | [jvm]<br>abstract fun [getRate](get-rate.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>how many times per time unit the event will happen on average |
| [update](update.md) | [jvm]<br>abstract fun [update](update.md)(currentTime: [Time](../-time/index.md), executed: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), param: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), environment: [Environment](../-environment/index.md)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.md), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>)<br>Updates the internal status. |

## Inheritors

| Name |
|---|
| [AbstractDistribution](../../it.unibo.alchemist.model.implementations.timedistributions/-abstract-distribution/index.md) |
| [SAPERETimeDistribution](../../it.unibo.alchemist.model.implementations.timedistributions/-s-a-p-e-r-e-time-distribution/index.md) |
