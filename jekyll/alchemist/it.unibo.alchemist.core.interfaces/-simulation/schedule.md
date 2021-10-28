---
title: schedule
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.core.interfaces](../index.html)/[Simulation](index.html)/[schedule](schedule.html)



# schedule



[jvm]\
abstract fun [schedule](schedule.html)(r: CheckedRunnable)



Schedules a runnable to be executed by the Simulation thread, useful for synchronization purposes (e.g. make sure that the environment is not being changed while the requested operation is being executed). An exception thrown by the passed runnable will make the simulation terminate.



## Parameters


jvm

| | |
|---|---|
| r | the runnable to execute |




