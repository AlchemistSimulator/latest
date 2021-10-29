//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.timedistributions](../index.md)/[Trigger](index.md)

# Trigger

[jvm]\
class [Trigger](index.md)<[T](index.md)> : [AbstractDistribution](../-abstract-distribution/index.md)<[T](../../it.unibo.alchemist/-supported-incarnations/get.md)>

## Parameters

jvm

| | |
|---|---|
| <T> | Concentration type |

## Constructors

| | |
|---|---|
| [Trigger](-trigger.md) | [jvm]<br>open fun [Trigger](-trigger.md)(event: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md))<br>the time at which the event will happen |

## Functions

| Name | Summary |
|---|---|
| [cloneOnNewNode](clone-on-new-node.md) | [jvm]<br>open fun [cloneOnNewNode](clone-on-new-node.md)(destination: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist/-supported-incarnations/get.md)>, currentTime: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md)): [Trigger](index.md)<[T](../../it.unibo.alchemist/-supported-incarnations/get.md)><br>abstract fun [cloneOnNewNode](../../it.unibo.alchemist.model.interfaces/-time-distribution/clone-on-new-node.md)(p: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist/-supported-incarnations/get.md)>, p1: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md)): [TimeDistribution](../../it.unibo.alchemist.model.interfaces/-time-distribution/index.md)<[T](../../it.unibo.alchemist/-supported-incarnations/get.md)> |
| [getNextOccurence](../-abstract-distribution/get-next-occurence.md) | [jvm]<br>fun [getNextOccurence](../-abstract-distribution/get-next-occurence.md)(): [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md)<br>abstract fun [getNextOccurence](../../it.unibo.alchemist.model.interfaces/-time-distribution/get-next-occurence.md)(): [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md) |
| [getRate](get-rate.md) | [jvm]<br>open fun [getRate](get-rate.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [update](../-abstract-distribution/update.md) | [jvm]<br>fun [update](../-abstract-distribution/update.md)(currentTime: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md), hasBeenExecuted: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), additionalParameter: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](../../it.unibo.alchemist/-supported-incarnations/get.md), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>)<br>abstract fun [update](../../it.unibo.alchemist.model.interfaces/-time-distribution/update.md)(p: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md), p1: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), p2: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), p3: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](../../it.unibo.alchemist/-supported-incarnations/get.md), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |
