---
title: OutputMonitor
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.interfaces](../index.html)/[OutputMonitor](index.html)



# OutputMonitor



[jvm]\
interface [OutputMonitor](index.html)<[T](index.html), [P](index.html) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<out [P](index.html)>?> : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)

An interface for the visualization of the simulation.



## Parameters


jvm

| | |
|---|---|
| <T> | Concentration Type |
| <P> | [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html) Type |



## Functions


| Name | Summary |
|---|---|
| [finished](finished.html) | [jvm]<br>abstract fun [finished](finished.html)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](index.html), [P](index.html)>, time: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html), step: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html))<br>This method will be called by the simulation once the whole simulation has finished, either because it reached its latest point or because the user stopped it. |
| [initialized](initialized.html) | [jvm]<br>abstract fun [initialized](initialized.html)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](index.html), [P](index.html)>)<br>This method will be called by the simulation as soon as the initialization phase is completed. |
| [stepDone](step-done.html) | [jvm]<br>abstract fun [stepDone](step-done.html)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](index.html), [P](index.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](index.html)>, time: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html), step: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html))<br>This method will be called by the simulation every time a simulation step is done. |


## Inheritors


| Name |
|---|
| [Exporter](../../it.unibo.alchemist.loader.export/-exporter/index.html) |
| [PlayPauseMonitor](../../it.unibo.alchemist.boundary.monitor/-play-pause-monitor/index.html) |
| [NumericLabelMonitor](../../it.unibo.alchemist.boundary.monitor.generic/-numeric-label-monitor/index.html) |
| [FXOutputMonitor](../-f-x-output-monitor/index.html) |
| [GraphicalOutputMonitor](../-graphical-output-monitor/index.html) |
| [TimeStepMonitor](../../it.unibo.alchemist.boundary.monitors/-time-step-monitor/index.html) |
| [NodeTracker](../../it.unibo.alchemist.boundary.monitors/-node-tracker/index.html) |

