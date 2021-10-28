//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.interfaces](../index.md)/[OutputMonitor](index.md)/[finished](finished.md)

# finished

[jvm]\
abstract fun [finished](finished.md)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](index.md), [P](index.md)>, time: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md), step: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html))

This method will be called by the simulation once the whole simulation has finished, either because it reached its latest point or because the user stopped it. Thread safety note: no specific policy is defined for the control flow which will execute this method. A new thread could have been spawned or the same flow of the simulation may execute this method. This depends on the specific [it.unibo.alchemist.core.interfaces.Simulation](../../it.unibo.alchemist.core.interfaces/-simulation/index.md) implementation.

## Parameters

jvm

| | |
|---|---|
| environment | The current environment |
| time | The time at which the simulation ended |
| step | The last step number |
