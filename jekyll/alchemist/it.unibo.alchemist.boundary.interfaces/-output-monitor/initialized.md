---
title: initialized
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.interfaces](../index.html)/[OutputMonitor](index.html)/[initialized](initialized.html)



# initialized



[jvm]\
abstract fun [initialized](initialized.html)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../../it.unibo.alchemist.core.interfaces/-scheduler/index.html), [P](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html)>)



This method will be called by the simulation as soon as the initialization phase is completed. Thread safety note: no specific policy is defined for the control flow which will execute this method. A new thread could have been spawned or the same flow of the simulation may execute this method. This depends on the specific [it.unibo.alchemist.core.interfaces.Simulation](../../it.unibo.alchemist.core.interfaces/-simulation/index.html) implementation.



## Parameters


jvm

| | |
|---|---|
| environment | the environment |




