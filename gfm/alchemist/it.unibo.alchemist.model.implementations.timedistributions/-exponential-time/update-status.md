//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.timedistributions](../index.md)/[ExponentialTime](index.md)/[updateStatus](update-status.md)

# updateStatus

[jvm]\
fun [updateStatus](update-status.md)(currentTime: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md), executed: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), newpropensity: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.md), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>)

Implement this method to update the distribution's internal status.

## Parameters

jvm

| | |
|---|---|
| currentTime | current time |
| executed | true if the reaction whose this distribution has been associated has just been executed |
| param | optional parameter passed by the reaction |
| environment | the current environment |
