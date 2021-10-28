//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces](../index.md)/[Reaction](index.md)

# Reaction

[jvm]\
interface [Reaction](index.md)<[T](index.md)> : [Comparable](https://docs.oracle.com/javase/8/docs/api/java/lang/Comparable.html)<[Reaction](index.md)<[T](../-action/index.md)>> , [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)

## Parameters

jvm

| | |
|---|---|
| <T> | The type which describes the concentration of a molecule A generic reaction. Every reaction in the system must implement this interface. |

## Functions

| Name | Summary |
|---|---|
| [canExecute](can-execute.md) | [jvm]<br>abstract fun [canExecute](can-execute.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>true if the reaction can be executed (namely, all the conditions are satisfied). |
| [cloneOnNewNode](clone-on-new-node.md) | [jvm]<br>abstract fun [cloneOnNewNode](clone-on-new-node.md)(node: [Node](../-node/index.md)<[T](../-action/index.md)>, currentTime: [Time](../-time/index.md)): [Reaction](index.md)<[T](../-action/index.md)><br>This method allows to clone this reaction on a new node. |
| [compareTo](../-g-p-s-point/index.md#-1554281679%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [compareTo](../-g-p-s-point/index.md#-1554281679%2FFunctions%2F-267951372)(p: [T](../-action/index.md)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [execute](execute.md) | [jvm]<br>abstract fun [execute](execute.md)()<br>Executes the reactions. |
| [getActions](get-actions.md) | [jvm]<br>abstract fun [getActions](get-actions.md)(): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[Action](../-action/index.md)<[T](../-action/index.md)>><br>The list of [Action](../-action/index.md)s of the [Reaction](index.md). |
| [getConditions](get-conditions.md) | [jvm]<br>abstract fun [getConditions](get-conditions.md)(): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[Condition](../-condition/index.md)<[T](../-action/index.md)>><br>The list of [Condition](../-condition/index.md)s of the [Reaction](index.md). |
| [getInboundDependencies](get-inbound-dependencies.md) | [jvm]<br>abstract fun [getInboundDependencies](get-inbound-dependencies.md)(): ListSet<out [Dependency](../-dependency/index.md)><br>The list of [Dependency](../-dependency/index.md)s whose concentration may affect the execution of the [Reaction](index.md). |
| [getInputContext](get-input-context.md) | [jvm]<br>abstract fun [getInputContext](get-input-context.md)(): [Context](../-context/index.md)<br>The widest [Context](../-context/index.md) among [Condition](../-condition/index.md)s, namely the smallest [Context](../-context/index.md) in which the [Reaction](index.md) can read informations. |
| [getNode](get-node.md) | [jvm]<br>abstract fun [getNode](get-node.md)(): [Node](../-node/index.md)<[T](../-action/index.md)><br>The [Node](../-node/index.md) in which this [Reaction](index.md) executes. |
| [getOutboundDependencies](get-outbound-dependencies.md) | [jvm]<br>abstract fun [getOutboundDependencies](get-outbound-dependencies.md)(): ListSet<out [Dependency](../-dependency/index.md)><br>The list of [Dependency](../-dependency/index.md) whose concentration may change after the execution of this reaction. |
| [getOutputContext](get-output-context.md) | [jvm]<br>abstract fun [getOutputContext](get-output-context.md)(): [Context](../-context/index.md)<br>The widest [Context](../-context/index.md) among [Action](../-action/index.md)s, namely the smallest context in which the [Reaction](index.md) can do modifications. |
| [getRate](get-rate.md) | [jvm]<br>abstract fun [getRate](get-rate.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Returns the speed of this [Reaction](index.md). |
| [getTau](get-tau.md) | [jvm]<br>abstract fun [getTau](get-tau.md)(): [Time](../-time/index.md)<br>The global [Time](../-time/index.md) at which this reaction is scheduled to be executed |
| [getTimeDistribution](get-time-distribution.md) | [jvm]<br>abstract fun [getTimeDistribution](get-time-distribution.md)(): [TimeDistribution](../-time-distribution/index.md)<[T](../-action/index.md)><br>the [TimeDistribution](../-time-distribution/index.md) for this [Reaction](index.md) |
| [initializationComplete](initialization-complete.md) | [jvm]<br>abstract fun [initializationComplete](initialization-complete.md)(atTime: [Time](../-time/index.md), environment: [Environment](../-environment/index.md)<[T](../-action/index.md), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>)<br>This method is called when the environment has completed its initialization. |
| [setActions](set-actions.md) | [jvm]<br>abstract fun [setActions](set-actions.md)(actions: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[Action](../-action/index.md)<[T](../-action/index.md)>>)<br>Sets the [Action](../-action/index.md)s list. |
| [setConditions](set-conditions.md) | [jvm]<br>abstract fun [setConditions](set-conditions.md)(conditions: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[Condition](../-condition/index.md)<[T](../-action/index.md)>>)<br>Sets the [Condition](../-condition/index.md)s list. |
| [update](update.md) | [jvm]<br>abstract fun [update](update.md)(currentTime: [Time](../-time/index.md), hasBeenExecuted: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), environment: [Environment](../-environment/index.md)<[T](../-action/index.md), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>)<br>Updates the scheduling of this reaction. |

## Inheritors

| Name |
|---|
| [AbstractReaction](../../it.unibo.alchemist.model.implementations.reactions/-abstract-reaction/index.md) |
