//[alchemist](../../../index.md)/[it.unibo.alchemist.core.interfaces](../index.md)/[Simulation](index.md)/[schedule](schedule.md)

# schedule

[jvm]\
abstract fun [schedule](schedule.md)(r: CheckedRunnable)

Schedules a runnable to be executed by the Simulation thread, useful for synchronization purposes (e.g. make sure that the environment is not being changed while the requested operation is being executed). An exception thrown by the passed runnable will make the simulation terminate.

## Parameters

jvm

| | |
|---|---|
| r | the runnable to execute |
