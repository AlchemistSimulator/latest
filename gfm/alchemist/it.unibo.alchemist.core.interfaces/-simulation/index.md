//[alchemist](../../../index.md)/[it.unibo.alchemist.core.interfaces](../index.md)/[Simulation](index.md)

# Simulation

[jvm]\
interface [Simulation](index.md)<[T](index.md), [P](index.md) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<out [P](index.md)>?> : [Runnable](https://docs.oracle.com/javase/8/docs/api/java/lang/Runnable.html)

This interface forces simulations to be independent threads, and make them controllable from an external console.

## Parameters

jvm

| | |
|---|---|
| <T> | Concentration type |
| <P> | Position Type |

## Functions

| Name | Summary |
|---|---|
| [addOutputMonitor](add-output-monitor.md) | [jvm]<br>abstract fun [addOutputMonitor](add-output-monitor.md)(op: [OutputMonitor](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.md)<[T](../../it.unibo.alchemist.model.interfaces/-action/index.md), [P](index.md)>)<br>Adds an [OutputMonitor](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.md) to this simulation. |
| [getEnvironment](get-environment.md) | [jvm]<br>abstract fun [getEnvironment](get-environment.md)(): [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](../../it.unibo.alchemist.model.interfaces/-action/index.md), [P](index.md)><br>Allows to access the current environment. |
| [getError](get-error.md) | [jvm]<br>abstract fun [getError](get-error.md)(): [Optional](https://docs.oracle.com/javase/8/docs/api/java/util/Optional.html)<[Throwable](https://docs.oracle.com/javase/8/docs/api/java/lang/Throwable.html)><br>an [Optional](https://docs.oracle.com/javase/8/docs/api/java/util/Optional.html) containing the exception that made the simulation fail, or [empty](https://docs.oracle.com/javase/8/docs/api/java/util/Optional.html#empty--) in case the simulation is ongoing or has terminated successfully. |
| [getFinalStep](get-final-step.md) | [jvm]<br>abstract fun [getFinalStep](get-final-step.md)(): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)<br>the step at which this simulation will eventually stop. |
| [getFinalTime](get-final-time.md) | [jvm]<br>abstract fun [getFinalTime](get-final-time.md)(): [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md)<br>Allows to at which time this simulation will end. |
| [getStatus](get-status.md) | [jvm]<br>abstract fun [getStatus](get-status.md)(): [Status](../-status/index.md)<br>Allows to access the current status. |
| [getStep](get-step.md) | [jvm]<br>abstract fun [getStep](get-step.md)(): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)<br>Allows to access the current simulation step. |
| [getTime](get-time.md) | [jvm]<br>abstract fun [getTime](get-time.md)(): [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md)<br>Allows to know which is the current simulation time. |
| [goToStep](go-to-step.md) | [jvm]<br>abstract fun [goToStep](go-to-step.md)(steps: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html))<br>Executes a certain number of steps, then pauses it. |
| [goToTime](go-to-time.md) | [jvm]<br>abstract fun [goToTime](go-to-time.md)(t: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md))<br>Executes the simulation until the target time is reached, then pauses it. |
| [neighborAdded](neighbor-added.md) | [jvm]<br>abstract fun [neighborAdded](neighbor-added.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.interfaces/-action/index.md)>, n: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.interfaces/-action/index.md)>)<br>This method must get called in case a a communication link connecting two nodes gets created during the simulation. |
| [neighborRemoved](neighbor-removed.md) | [jvm]<br>abstract fun [neighborRemoved](neighbor-removed.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.interfaces/-action/index.md)>, n: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.interfaces/-action/index.md)>)<br>This method must get called in case a a communication link connecting two nodes gets broken during the simulation. |
| [nodeAdded](node-added.md) | [jvm]<br>abstract fun [nodeAdded](node-added.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.interfaces/-action/index.md)>)<br>This method must get called in case a node is added to the environment during the simulation and after its neighborhood has been computed (or can be consistently computed by the simulated environment). |
| [nodeMoved](node-moved.md) | [jvm]<br>abstract fun [nodeMoved](node-moved.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.interfaces/-action/index.md)>)<br>This method must get called in case a node is moved in the environment during the simulation and after its neighborhood has been computed (or can be consistently computed by the simulated environment). |
| [nodeRemoved](node-removed.md) | [jvm]<br>abstract fun [nodeRemoved](node-removed.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.interfaces/-action/index.md)>, oldNeighborhood: [Neighborhood](../../it.unibo.alchemist.model.interfaces/-neighborhood/index.md)<[T](../../it.unibo.alchemist.model.interfaces/-action/index.md)>)<br>This method must get called in case a node is removed from the environment during the simulation and after its neighborhood has been computed (or can be consistently computed by the simulated environment). |
| [pause](pause.md) | [jvm]<br>abstract fun [pause](pause.md)()<br>Sends a pause command to the simulation. |
| [play](play.md) | [jvm]<br>abstract fun [play](play.md)()<br>Sends a play command to the simulation. |
| [reactionAdded](reaction-added.md) | [jvm]<br>abstract fun [reactionAdded](reaction-added.md)(reactionToAdd: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](../../it.unibo.alchemist.model.interfaces/-action/index.md)>)<br>Adds a reaction during the simulation to the scheduler and start to execute it. |
| [reactionRemoved](reaction-removed.md) | [jvm]<br>abstract fun [reactionRemoved](reaction-removed.md)(reactionToRemove: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](../../it.unibo.alchemist.model.interfaces/-action/index.md)>)<br>Removes a reaction during the simulation from the scheduler and stop to execute it. |
| [removeOutputMonitor](remove-output-monitor.md) | [jvm]<br>abstract fun [removeOutputMonitor](remove-output-monitor.md)(op: [OutputMonitor](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.md)<[T](../../it.unibo.alchemist.model.interfaces/-action/index.md), [P](index.md)>)<br>Removes an [OutputMonitor](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.md) to this simulation. |
| [run](index.md#-853624561%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [run](index.md#-853624561%2FFunctions%2F-267951372)() |
| [schedule](schedule.md) | [jvm]<br>abstract fun [schedule](schedule.md)(r: CheckedRunnable)<br>Schedules a runnable to be executed by the Simulation thread, useful for synchronization purposes (e.g. |
| [terminate](terminate.md) | [jvm]<br>abstract fun [terminate](terminate.md)()<br>Sends a terminate command to the simulation. |
| [waitFor](wait-for.md) | [jvm]<br>abstract fun [waitFor](wait-for.md)(s: [Status](../-status/index.md), timeout: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), timeunit: [TimeUnit](https://docs.oracle.com/javase/8/docs/api/java/util/concurrent/TimeUnit.html)): [Status](../-status/index.md)<br>Suspends the caller until the simulation reaches the selected [Status](../-status/index.md) or the timeout ends. |

## Inheritors

| Name |
|---|
| [Engine](../../it.unibo.alchemist.core.implementations/-engine/index.md) |
