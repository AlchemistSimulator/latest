---
title: Simulation
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.core.interfaces](../index.html)/[Simulation](index.html)



# Simulation



[jvm]\
interface [Simulation](index.html)<[T](index.html), [P](index.html) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<out [P](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html)>?> : [Runnable](https://docs.oracle.com/javase/8/docs/api/java/lang/Runnable.html)

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
| [addOutputMonitor](add-output-monitor.html) | [jvm]<br>abstract fun [addOutputMonitor](add-output-monitor.html)(op: [OutputMonitor](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)<[T](../-scheduler/index.html), [P](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html)>)<br>Adds an [OutputMonitor](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html) to this simulation. |
| [getEnvironment](get-environment.html) | [jvm]<br>abstract fun [getEnvironment](get-environment.html)(): [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../-scheduler/index.html), [P](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html)><br>Allows to access the current environment. |
| [getError](get-error.html) | [jvm]<br>abstract fun [getError](get-error.html)(): [Optional](https://docs.oracle.com/javase/8/docs/api/java/util/Optional.html)<[Throwable](https://docs.oracle.com/javase/8/docs/api/java/lang/Throwable.html)><br>an [Optional](https://docs.oracle.com/javase/8/docs/api/java/util/Optional.html) containing the exception that made the simulation fail, or [empty](https://docs.oracle.com/javase/8/docs/api/java/util/Optional.html#empty--) in case the simulation is ongoing or has terminated successfully. |
| [getFinalStep](get-final-step.html) | [jvm]<br>abstract fun [getFinalStep](get-final-step.html)(): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)<br>the step at which this simulation will eventually stop. |
| [getFinalTime](get-final-time.html) | [jvm]<br>abstract fun [getFinalTime](get-final-time.html)(): [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html)<br>Allows to at which time this simulation will end. |
| [getStatus](get-status.html) | [jvm]<br>abstract fun [getStatus](get-status.html)(): [Status](../-status/index.html)<br>Allows to access the current status. |
| [getStep](get-step.html) | [jvm]<br>abstract fun [getStep](get-step.html)(): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)<br>Allows to access the current simulation step. |
| [getTime](get-time.html) | [jvm]<br>abstract fun [getTime](get-time.html)(): [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html)<br>Allows to know which is the current simulation time. |
| [goToStep](go-to-step.html) | [jvm]<br>abstract fun [goToStep](go-to-step.html)(steps: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html))<br>Executes a certain number of steps, then pauses it. |
| [goToTime](go-to-time.html) | [jvm]<br>abstract fun [goToTime](go-to-time.html)(t: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html))<br>Executes the simulation until the target time is reached, then pauses it. |
| [neighborAdded](neighbor-added.html) | [jvm]<br>abstract fun [neighborAdded](neighbor-added.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../-scheduler/index.html)>, n: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../-scheduler/index.html)>)<br>This method must get called in case a a communication link connecting two nodes gets created during the simulation. |
| [neighborRemoved](neighbor-removed.html) | [jvm]<br>abstract fun [neighborRemoved](neighbor-removed.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../-scheduler/index.html)>, n: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../-scheduler/index.html)>)<br>This method must get called in case a a communication link connecting two nodes gets broken during the simulation. |
| [nodeAdded](node-added.html) | [jvm]<br>abstract fun [nodeAdded](node-added.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../-scheduler/index.html)>)<br>This method must get called in case a node is added to the environment during the simulation and after its neighborhood has been computed (or can be consistently computed by the simulated environment). |
| [nodeMoved](node-moved.html) | [jvm]<br>abstract fun [nodeMoved](node-moved.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../-scheduler/index.html)>)<br>This method must get called in case a node is moved in the environment during the simulation and after its neighborhood has been computed (or can be consistently computed by the simulated environment). |
| [nodeRemoved](node-removed.html) | [jvm]<br>abstract fun [nodeRemoved](node-removed.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../-scheduler/index.html)>, oldNeighborhood: [Neighborhood](../../it.unibo.alchemist.model.interfaces/-neighborhood/index.html)<[T](../-scheduler/index.html)>)<br>This method must get called in case a node is removed from the environment during the simulation and after its neighborhood has been computed (or can be consistently computed by the simulated environment). |
| [pause](pause.html) | [jvm]<br>abstract fun [pause](pause.html)()<br>Sends a pause command to the simulation. |
| [play](play.html) | [jvm]<br>abstract fun [play](play.html)()<br>Sends a play command to the simulation. |
| [reactionAdded](reaction-added.html) | [jvm]<br>abstract fun [reactionAdded](reaction-added.html)(reactionToAdd: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../-scheduler/index.html)>)<br>Adds a reaction during the simulation to the scheduler and start to execute it. |
| [reactionRemoved](reaction-removed.html) | [jvm]<br>abstract fun [reactionRemoved](reaction-removed.html)(reactionToRemove: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../-scheduler/index.html)>)<br>Removes a reaction during the simulation from the scheduler and stop to execute it. |
| [removeOutputMonitor](remove-output-monitor.html) | [jvm]<br>abstract fun [removeOutputMonitor](remove-output-monitor.html)(op: [OutputMonitor](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)<[T](../-scheduler/index.html), [P](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html)>)<br>Removes an [OutputMonitor](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html) to this simulation. |
| [run](index.html#-853624561%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [run](index.html#-853624561%2FFunctions%2F-134779887)() |
| [schedule](schedule.html) | [jvm]<br>abstract fun [schedule](schedule.html)(r: CheckedRunnable)<br>Schedules a runnable to be executed by the Simulation thread, useful for synchronization purposes (e.g. |
| [terminate](terminate.html) | [jvm]<br>abstract fun [terminate](terminate.html)()<br>Sends a terminate command to the simulation. |
| [waitFor](wait-for.html) | [jvm]<br>abstract fun [waitFor](wait-for.html)(s: [Status](../-status/index.html), timeout: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), timeunit: [TimeUnit](https://docs.oracle.com/javase/8/docs/api/java/util/concurrent/TimeUnit.html)): [Status](../-status/index.html)<br>Suspends the caller until the simulation reaches the selected [Status](../-status/index.html) or the timeout ends. |


## Inheritors


| Name |
|---|
| [Engine](../../it.unibo.alchemist.core.implementations/-engine/index.html) |

