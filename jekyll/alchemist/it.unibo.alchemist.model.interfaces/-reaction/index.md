---
title: Reaction
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces](../index.html)/[Reaction](index.html)



# Reaction



[jvm]\
interface [Reaction](index.html)<[T](index.html)> : [Comparable](https://docs.oracle.com/javase/8/docs/api/java/lang/Comparable.html)<[Reaction](index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)>> , [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)



## Parameters


jvm

| | |
|---|---|
| <T> | The type which describes the concentration of a molecule A generic reaction. Every reaction in the system must implement this interface. |



## Functions


| Name | Summary |
|---|---|
| [canExecute](can-execute.html) | [jvm]<br>abstract fun [canExecute](can-execute.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>true if the reaction can be executed (namely, all the conditions are satisfied). |
| [cloneOnNewNode](clone-on-new-node.html) | [jvm]<br>abstract fun [cloneOnNewNode](clone-on-new-node.html)(node: [Node](../-node/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)>, currentTime: [Time](../-time/index.html)): [Reaction](index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)><br>This method allows to clone this reaction on a new node. |
| [compareTo](../-g-p-s-point/index.html#-1554281679%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [compareTo](../-g-p-s-point/index.html#-1554281679%2FFunctions%2F-134779887)(p: [T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [execute](execute.html) | [jvm]<br>abstract fun [execute](execute.html)()<br>Executes the reactions. |
| [getActions](get-actions.html) | [jvm]<br>abstract fun [getActions](get-actions.html)(): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[Action](../-action/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)>><br>The list of [Action](../-action/index.html)s of the [Reaction](index.html). |
| [getConditions](get-conditions.html) | [jvm]<br>abstract fun [getConditions](get-conditions.html)(): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[Condition](../-condition/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)>><br>The list of [Condition](../-condition/index.html)s of the [Reaction](index.html). |
| [getInboundDependencies](get-inbound-dependencies.html) | [jvm]<br>abstract fun [getInboundDependencies](get-inbound-dependencies.html)(): ListSet<out [Dependency](../-dependency/index.html)><br>The list of [Dependency](../-dependency/index.html)s whose concentration may affect the execution of the [Reaction](index.html). |
| [getInputContext](get-input-context.html) | [jvm]<br>abstract fun [getInputContext](get-input-context.html)(): [Context](../-context/index.html)<br>The widest [Context](../-context/index.html) among [Condition](../-condition/index.html)s, namely the smallest [Context](../-context/index.html) in which the [Reaction](index.html) can read informations. |
| [getNode](get-node.html) | [jvm]<br>abstract fun [getNode](get-node.html)(): [Node](../-node/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)><br>The [Node](../-node/index.html) in which this [Reaction](index.html) executes. |
| [getOutboundDependencies](get-outbound-dependencies.html) | [jvm]<br>abstract fun [getOutboundDependencies](get-outbound-dependencies.html)(): ListSet<out [Dependency](../-dependency/index.html)><br>The list of [Dependency](../-dependency/index.html) whose concentration may change after the execution of this reaction. |
| [getOutputContext](get-output-context.html) | [jvm]<br>abstract fun [getOutputContext](get-output-context.html)(): [Context](../-context/index.html)<br>The widest [Context](../-context/index.html) among [Action](../-action/index.html)s, namely the smallest context in which the [Reaction](index.html) can do modifications. |
| [getRate](get-rate.html) | [jvm]<br>abstract fun [getRate](get-rate.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Returns the speed of this [Reaction](index.html). |
| [getTau](get-tau.html) | [jvm]<br>abstract fun [getTau](get-tau.html)(): [Time](../-time/index.html)<br>The global [Time](../-time/index.html) at which this reaction is scheduled to be executed |
| [getTimeDistribution](get-time-distribution.html) | [jvm]<br>abstract fun [getTimeDistribution](get-time-distribution.html)(): [TimeDistribution](../-time-distribution/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)><br>the [TimeDistribution](../-time-distribution/index.html) for this [Reaction](index.html) |
| [initializationComplete](initialization-complete.html) | [jvm]<br>abstract fun [initializationComplete](initialization-complete.html)(atTime: [Time](../-time/index.html), environment: [Environment](../-environment/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>)<br>This method is called when the environment has completed its initialization. |
| [setActions](set-actions.html) | [jvm]<br>abstract fun [setActions](set-actions.html)(actions: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[Action](../-action/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)>>)<br>Sets the [Action](../-action/index.html)s list. |
| [setConditions](set-conditions.html) | [jvm]<br>abstract fun [setConditions](set-conditions.html)(conditions: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[Condition](../-condition/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)>>)<br>Sets the [Condition](../-condition/index.html)s list. |
| [update](update.html) | [jvm]<br>abstract fun [update](update.html)(currentTime: [Time](../-time/index.html), hasBeenExecuted: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), environment: [Environment](../-environment/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>)<br>Updates the scheduling of this reaction. |


## Inheritors


| Name |
|---|
| [AbstractReaction](../../it.unibo.alchemist.model.implementations.reactions/-abstract-reaction/index.html) |

