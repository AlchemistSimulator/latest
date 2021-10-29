//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.interfaces](../index.md)/[OutputMonitor](index.md)/[stepDone](step-done.md)

# stepDone

[jvm]\
abstract fun [stepDone](step-done.md)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](../../it.unibo.alchemist.model.interfaces/-node/index.md), [P](../../it.unibo.alchemist.model.interfaces/-benchmarkable-environment/index.md)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](../../it.unibo.alchemist.model.interfaces/-node/index.md)>, time: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md), step: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html))

This method will be called by the simulation every time a simulation step is done. Thread safety note: no specific policy is defined for the control flow which will execute this method. A new thread could have been spawned or the same flow of the simulation may execute this method. This depends on the specific [it.unibo.alchemist.core.interfaces.Simulation](../../it.unibo.alchemist.core.interfaces/-simulation/index.md) implementation.

## Parameters

jvm

| | |
|---|---|
| environment | The current environment |
| reaction | The last reaction executed |
| time | The time at this simulation point |
| step | The current simulation step |
