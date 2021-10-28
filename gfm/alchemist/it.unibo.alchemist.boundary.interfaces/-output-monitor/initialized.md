//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.interfaces](../index.md)/[OutputMonitor](index.md)/[initialized](initialized.md)

# initialized

[jvm]\
abstract fun [initialized](initialized.md)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](../../it.unibo.alchemist.model.interfaces/-action/index.md), [P](../../it.unibo.alchemist.core.interfaces/-simulation/index.md)>)

This method will be called by the simulation as soon as the initialization phase is completed. Thread safety note: no specific policy is defined for the control flow which will execute this method. A new thread could have been spawned or the same flow of the simulation may execute this method. This depends on the specific [it.unibo.alchemist.core.interfaces.Simulation](../../it.unibo.alchemist.core.interfaces/-simulation/index.md) implementation.

## Parameters

jvm

| | |
|---|---|
| environment | the environment |
