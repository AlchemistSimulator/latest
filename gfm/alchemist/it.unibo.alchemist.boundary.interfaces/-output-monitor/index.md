//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.interfaces](../index.md)/[OutputMonitor](index.md)

# OutputMonitor

[jvm]\
interface [OutputMonitor](index.md)<[T](index.md), [P](index.md) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<out [P](index.md)>?> : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)

An interface for the visualization of the simulation.

## Parameters

jvm

| | |
|---|---|
| <T> | Concentration Type |
| <P> | [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md) Type |

## Functions

| Name | Summary |
|---|---|
| [finished](finished.md) | [jvm]<br>abstract fun [finished](finished.md)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](index.md), [P](index.md)>, time: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md), step: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html))<br>This method will be called by the simulation once the whole simulation has finished, either because it reached its latest point or because the user stopped it. |
| [initialized](initialized.md) | [jvm]<br>abstract fun [initialized](initialized.md)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](index.md), [P](index.md)>)<br>This method will be called by the simulation as soon as the initialization phase is completed. |
| [stepDone](step-done.md) | [jvm]<br>abstract fun [stepDone](step-done.md)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](index.md), [P](index.md)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](index.md)>, time: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md), step: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html))<br>This method will be called by the simulation every time a simulation step is done. |

## Inheritors

| Name |
|---|
| [Exporter](../../it.unibo.alchemist.loader.export/-exporter/index.md) |
| [PlayPauseMonitor](../../it.unibo.alchemist.boundary.monitor/-play-pause-monitor/index.md) |
| [NumericLabelMonitor](../../it.unibo.alchemist.boundary.monitor.generic/-numeric-label-monitor/index.md) |
| [FXOutputMonitor](../-f-x-output-monitor/index.md) |
| [GraphicalOutputMonitor](../-graphical-output-monitor/index.md) |
| [TimeStepMonitor](../../it.unibo.alchemist.boundary.monitors/-time-step-monitor/index.md) |
| [NodeTracker](../../it.unibo.alchemist.boundary.monitors/-node-tracker/index.md) |
