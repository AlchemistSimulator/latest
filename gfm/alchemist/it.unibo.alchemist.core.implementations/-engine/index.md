//[alchemist](../../../index.md)/[it.unibo.alchemist.core.implementations](../index.md)/[Engine](index.md)

# Engine

[jvm]\
class [Engine](index.md)<[T](index.md), [P](index.md) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<out [P](index.md)>?> : [Simulation](../../it.unibo.alchemist.core.interfaces/-simulation/index.md)<[T](../-array-indexed-priority-queue/index.md), [P](index.md)> 

This class implements a simulation. It offers a wide number of static factories to ease the creation process.

## Parameters

jvm

| | |
|---|---|
| <T> | concentration type |
| <P> | [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md) type |

## Constructors

| | |
|---|---|
| [Engine](-engine.md) | [jvm]<br>open fun [Engine](-engine.md)(e: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](../-array-indexed-priority-queue/index.md), [P](index.md)>)<br>Builds a simulation for a given environment. |
| [Engine](-engine.md) | [jvm]<br>open fun [Engine](-engine.md)(e: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](../-array-indexed-priority-queue/index.md), [P](index.md)>, maxSteps: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html))<br>Builds a simulation for a given environment. |
| [Engine](-engine.md) | [jvm]<br>open fun [Engine](-engine.md)(e: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](../-array-indexed-priority-queue/index.md), [P](index.md)>, maxSteps: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), t: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md))<br>Builds a simulation for a given environment. |
| [Engine](-engine.md) | [jvm]<br>open fun [Engine](-engine.md)(e: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](../-array-indexed-priority-queue/index.md), [P](index.md)>, t: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md))<br>Builds a simulation for a given environment. |

## Functions

| Name | Summary |
|---|---|
| [addOutputMonitor](add-output-monitor.md) | [jvm]<br>open fun [addOutputMonitor](add-output-monitor.md)(op: [OutputMonitor](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.md)<[T](../-array-indexed-priority-queue/index.md), [P](index.md)>) |
| [getEnvironment](../../it.unibo.alchemist.core.interfaces/-simulation/get-environment.md) | [jvm]<br>abstract fun [getEnvironment](../../it.unibo.alchemist.core.interfaces/-simulation/get-environment.md)(): [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](../-array-indexed-priority-queue/index.md), [P](index.md)> |
| [getError](../../it.unibo.alchemist.core.interfaces/-simulation/get-error.md) | [jvm]<br>abstract fun [getError](../../it.unibo.alchemist.core.interfaces/-simulation/get-error.md)(): [Optional](https://docs.oracle.com/javase/8/docs/api/java/util/Optional.html)<[Throwable](https://docs.oracle.com/javase/8/docs/api/java/lang/Throwable.html)> |
| [getFinalStep](../../it.unibo.alchemist.core.interfaces/-simulation/get-final-step.md) | [jvm]<br>abstract fun [getFinalStep](../../it.unibo.alchemist.core.interfaces/-simulation/get-final-step.md)(): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [getFinalTime](../../it.unibo.alchemist.core.interfaces/-simulation/get-final-time.md) | [jvm]<br>abstract fun [getFinalTime](../../it.unibo.alchemist.core.interfaces/-simulation/get-final-time.md)(): [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md) |
| [getStatus](../../it.unibo.alchemist.core.interfaces/-simulation/get-status.md) | [jvm]<br>abstract fun [getStatus](../../it.unibo.alchemist.core.interfaces/-simulation/get-status.md)(): [Status](../../it.unibo.alchemist.core.interfaces/-status/index.md) |
| [getStep](get-step.md) | [jvm]<br>open fun [getStep](get-step.md)(): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [getTime](get-time.md) | [jvm]<br>open fun [getTime](get-time.md)(): [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md) |
| [goToStep](go-to-step.md) | [jvm]<br>open fun [goToStep](go-to-step.md)(step: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)) |
| [goToTime](go-to-time.md) | [jvm]<br>open fun [goToTime](go-to-time.md)(t: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md)) |
| [neighborAdded](neighbor-added.md) | [jvm]<br>open fun [neighborAdded](neighbor-added.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../-array-indexed-priority-queue/index.md)>, n: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../-array-indexed-priority-queue/index.md)>) |
| [neighborRemoved](neighbor-removed.md) | [jvm]<br>open fun [neighborRemoved](neighbor-removed.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../-array-indexed-priority-queue/index.md)>, n: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../-array-indexed-priority-queue/index.md)>) |
| [nodeAdded](node-added.md) | [jvm]<br>open fun [nodeAdded](node-added.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../-array-indexed-priority-queue/index.md)>) |
| [nodeMoved](node-moved.md) | [jvm]<br>open fun [nodeMoved](node-moved.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../-array-indexed-priority-queue/index.md)>) |
| [nodeRemoved](node-removed.md) | [jvm]<br>open fun [nodeRemoved](node-removed.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../-array-indexed-priority-queue/index.md)>, oldNeighborhood: [Neighborhood](../../it.unibo.alchemist.model.interfaces/-neighborhood/index.md)<[T](../-array-indexed-priority-queue/index.md)>) |
| [pause](pause.md) | [jvm]<br>open fun [pause](pause.md)() |
| [play](play.md) | [jvm]<br>open fun [play](play.md)() |
| [reactionAdded](reaction-added.md) | [jvm]<br>open fun [reactionAdded](reaction-added.md)(reactionToAdd: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](../-array-indexed-priority-queue/index.md)>) |
| [reactionRemoved](reaction-removed.md) | [jvm]<br>open fun [reactionRemoved](reaction-removed.md)(reactionToRemove: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](../-array-indexed-priority-queue/index.md)>) |
| [removeOutputMonitor](remove-output-monitor.md) | [jvm]<br>open fun [removeOutputMonitor](remove-output-monitor.md)(op: [OutputMonitor](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.md)<[T](../-array-indexed-priority-queue/index.md), [P](index.md)>) |
| [run](run.md) | [jvm]<br>open fun [run](run.md)() |
| [schedule](schedule.md) | [jvm]<br>open fun [schedule](schedule.md)(r: CheckedRunnable) |
| [terminate](terminate.md) | [jvm]<br>open fun [terminate](terminate.md)() |
| [toString](to-string.md) | [jvm]<br>open fun [toString](to-string.md)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |
| [waitFor](wait-for.md) | [jvm]<br>open fun [waitFor](wait-for.md)(next: [Status](../../it.unibo.alchemist.core.interfaces/-status/index.md), timeout: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), tu: [TimeUnit](https://docs.oracle.com/javase/8/docs/api/java/util/concurrent/TimeUnit.html)): [Status](../../it.unibo.alchemist.core.interfaces/-status/index.md) |

## Properties

| Name | Summary |
|---|---|
| [environment](environment.md) | [jvm]<br>private val [environment](environment.md): [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](../-array-indexed-priority-queue/index.md), [P](index.md)> |
| [error](error.md) | [jvm]<br>private open val [error](error.md): [Optional](https://docs.oracle.com/javase/8/docs/api/java/util/Optional.html)<[Throwable](https://docs.oracle.com/javase/8/docs/api/java/lang/Throwable.html)> |
| [finalStep](final-step.md) | [jvm]<br>private val [finalStep](final-step.md): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [finalTime](final-time.md) | [jvm]<br>private val [finalTime](final-time.md): [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md) |
| [status](status.md) | [jvm]<br>private open val [status](status.md): [Status](../../it.unibo.alchemist.core.interfaces/-status/index.md) |
