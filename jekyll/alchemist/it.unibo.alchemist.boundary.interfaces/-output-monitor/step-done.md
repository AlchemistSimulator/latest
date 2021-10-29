---
title: stepDone
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.interfaces](../index.html)/[OutputMonitor](index.html)/[stepDone](step-done.html)



# stepDone



[jvm]\
abstract fun [stepDone](step-done.html)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../../it.unibo.alchemist.core.interfaces/-scheduler/index.html), [P](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist.core.interfaces/-scheduler/index.html)>, time: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html), step: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html))



This method will be called by the simulation every time a simulation step is done. Thread safety note: no specific policy is defined for the control flow which will execute this method. A new thread could have been spawned or the same flow of the simulation may execute this method. This depends on the specific [it.unibo.alchemist.core.interfaces.Simulation](../../it.unibo.alchemist.core.interfaces/-simulation/index.html) implementation.



## Parameters


jvm

| | |
|---|---|
| environment | The current environment |
| reaction | The last reaction executed |
| time | The time at this simulation point |
| step | The current simulation step |




