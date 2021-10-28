//[alchemist](../../../index.md)/[it.unibo.alchemist.loader.export](../index.md)/[Time](index.md)/[extractData](extract-data.md)

# extractData

[jvm]\
open fun <[T](extract-data.md)> [extractData](extract-data.md)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](../../it.unibo.alchemist.loader/-loader/get-default.md), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](../../it.unibo.alchemist.loader/-loader/get-default.md)>, time: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md), step: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)>

Extracts numeric properties from an environment.

#### Return

the extracted properties

## Parameters

jvm

| | |
|---|---|
| environment | the [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md) |
| reaction | the last executed [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md) |
| time | the current [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md) |
| step | the simulation step |
| <T> | concentration type |
