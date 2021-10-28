---
title: Engine
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.core.implementations](../index.html)/[Engine](index.html)



# Engine



[jvm]\
class [Engine](index.html)<[T](index.html), [P](index.html) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<out [P](index.html)>?> : [Simulation](../../it.unibo.alchemist.core.interfaces/-simulation/index.html)<[T](../-array-indexed-priority-queue/index.html), [P](index.html)> 

This class implements a simulation. It offers a wide number of static factories to ease the creation process.



## Parameters


jvm

| | |
|---|---|
| <T> | concentration type |
| <P> | [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html) type |



## Constructors


| | |
|---|---|
| [Engine](-engine.html) | [jvm]<br>open fun [Engine](-engine.html)(e: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../-array-indexed-priority-queue/index.html), [P](index.html)>)<br>Builds a simulation for a given environment. |
| [Engine](-engine.html) | [jvm]<br>open fun [Engine](-engine.html)(e: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../-array-indexed-priority-queue/index.html), [P](index.html)>, maxSteps: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html))<br>Builds a simulation for a given environment. |
| [Engine](-engine.html) | [jvm]<br>open fun [Engine](-engine.html)(e: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../-array-indexed-priority-queue/index.html), [P](index.html)>, maxSteps: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), t: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html))<br>Builds a simulation for a given environment. |
| [Engine](-engine.html) | [jvm]<br>open fun [Engine](-engine.html)(e: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../-array-indexed-priority-queue/index.html), [P](index.html)>, t: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html))<br>Builds a simulation for a given environment. |


## Functions


| Name | Summary |
|---|---|
| [addOutputMonitor](add-output-monitor.html) | [jvm]<br>open fun [addOutputMonitor](add-output-monitor.html)(op: [OutputMonitor](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)<[T](../-array-indexed-priority-queue/index.html), [P](index.html)>) |
| [getEnvironment](../../it.unibo.alchemist.core.interfaces/-simulation/get-environment.html) | [jvm]<br>abstract fun [getEnvironment](../../it.unibo.alchemist.core.interfaces/-simulation/get-environment.html)(): [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../-array-indexed-priority-queue/index.html), [P](index.html)> |
| [getError](../../it.unibo.alchemist.core.interfaces/-simulation/get-error.html) | [jvm]<br>abstract fun [getError](../../it.unibo.alchemist.core.interfaces/-simulation/get-error.html)(): [Optional](https://docs.oracle.com/javase/8/docs/api/java/util/Optional.html)<[Throwable](https://docs.oracle.com/javase/8/docs/api/java/lang/Throwable.html)> |
| [getFinalStep](../../it.unibo.alchemist.core.interfaces/-simulation/get-final-step.html) | [jvm]<br>abstract fun [getFinalStep](../../it.unibo.alchemist.core.interfaces/-simulation/get-final-step.html)(): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [getFinalTime](../../it.unibo.alchemist.core.interfaces/-simulation/get-final-time.html) | [jvm]<br>abstract fun [getFinalTime](../../it.unibo.alchemist.core.interfaces/-simulation/get-final-time.html)(): [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html) |
| [getStatus](../../it.unibo.alchemist.core.interfaces/-simulation/get-status.html) | [jvm]<br>abstract fun [getStatus](../../it.unibo.alchemist.core.interfaces/-simulation/get-status.html)(): [Status](../../it.unibo.alchemist.core.interfaces/-status/index.html) |
| [getStep](get-step.html) | [jvm]<br>open fun [getStep](get-step.html)(): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [getTime](get-time.html) | [jvm]<br>open fun [getTime](get-time.html)(): [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html) |
| [goToStep](go-to-step.html) | [jvm]<br>open fun [goToStep](go-to-step.html)(step: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)) |
| [goToTime](go-to-time.html) | [jvm]<br>open fun [goToTime](go-to-time.html)(t: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html)) |
| [neighborAdded](neighbor-added.html) | [jvm]<br>open fun [neighborAdded](neighbor-added.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../-array-indexed-priority-queue/index.html)>, n: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../-array-indexed-priority-queue/index.html)>) |
| [neighborRemoved](neighbor-removed.html) | [jvm]<br>open fun [neighborRemoved](neighbor-removed.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../-array-indexed-priority-queue/index.html)>, n: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../-array-indexed-priority-queue/index.html)>) |
| [nodeAdded](node-added.html) | [jvm]<br>open fun [nodeAdded](node-added.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../-array-indexed-priority-queue/index.html)>) |
| [nodeMoved](node-moved.html) | [jvm]<br>open fun [nodeMoved](node-moved.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../-array-indexed-priority-queue/index.html)>) |
| [nodeRemoved](node-removed.html) | [jvm]<br>open fun [nodeRemoved](node-removed.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../-array-indexed-priority-queue/index.html)>, oldNeighborhood: [Neighborhood](../../it.unibo.alchemist.model.interfaces/-neighborhood/index.html)<[T](../-array-indexed-priority-queue/index.html)>) |
| [pause](pause.html) | [jvm]<br>open fun [pause](pause.html)() |
| [play](play.html) | [jvm]<br>open fun [play](play.html)() |
| [reactionAdded](reaction-added.html) | [jvm]<br>open fun [reactionAdded](reaction-added.html)(reactionToAdd: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../-array-indexed-priority-queue/index.html)>) |
| [reactionRemoved](reaction-removed.html) | [jvm]<br>open fun [reactionRemoved](reaction-removed.html)(reactionToRemove: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../-array-indexed-priority-queue/index.html)>) |
| [removeOutputMonitor](remove-output-monitor.html) | [jvm]<br>open fun [removeOutputMonitor](remove-output-monitor.html)(op: [OutputMonitor](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)<[T](../-array-indexed-priority-queue/index.html), [P](index.html)>) |
| [run](run.html) | [jvm]<br>open fun [run](run.html)() |
| [schedule](schedule.html) | [jvm]<br>open fun [schedule](schedule.html)(r: CheckedRunnable) |
| [terminate](terminate.html) | [jvm]<br>open fun [terminate](terminate.html)() |
| [toString](to-string.html) | [jvm]<br>open fun [toString](to-string.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |
| [waitFor](wait-for.html) | [jvm]<br>open fun [waitFor](wait-for.html)(next: [Status](../../it.unibo.alchemist.core.interfaces/-status/index.html), timeout: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), tu: [TimeUnit](https://docs.oracle.com/javase/8/docs/api/java/util/concurrent/TimeUnit.html)): [Status](../../it.unibo.alchemist.core.interfaces/-status/index.html) |


## Properties


| Name | Summary |
|---|---|
| [environment](environment.html) | [jvm]<br>private val [environment](environment.html): [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../-array-indexed-priority-queue/index.html), [P](index.html)> |
| [error](error.html) | [jvm]<br>private open val [error](error.html): [Optional](https://docs.oracle.com/javase/8/docs/api/java/util/Optional.html)<[Throwable](https://docs.oracle.com/javase/8/docs/api/java/lang/Throwable.html)> |
| [finalStep](final-step.html) | [jvm]<br>private val [finalStep](final-step.html): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [finalTime](final-time.html) | [jvm]<br>private val [finalTime](final-time.html): [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html) |
| [status](status.html) | [jvm]<br>private open val [status](status.html): [Status](../../it.unibo.alchemist.core.interfaces/-status/index.html) |

