//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces](../index.md)/[Condition](index.md)

# Condition

[jvm]\
interface [Condition](index.md)<[T](index.md)> : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)

## Parameters

jvm

| | |
|---|---|
| <T> | The type which describes the concentration of a molecule Interface of a condition. Every condition must implement this interface. |

## Functions

| Name | Summary |
|---|---|
| [cloneCondition](clone-condition.md) | [jvm]<br>abstract fun [cloneCondition](clone-condition.md)(node: [Node](../-node/index.md)<[T](../-action/index.md)>, reaction: [Reaction](../-reaction/index.md)<[T](../-action/index.md)>): [Condition](index.md)<[T](../-action/index.md)><br>This method allows to clone this action on a new node. |
| [getContext](get-context.md) | [jvm]<br>abstract fun [getContext](get-context.md)(): [Context](../-context/index.md)<br>The context for this condition. |
| [getInboundDependencies](get-inbound-dependencies.md) | [jvm]<br>abstract fun [getInboundDependencies](get-inbound-dependencies.md)(): ListSet<out [Dependency](../-dependency/index.md)><br>The list of molecules whose concentration may influence the truth value of this condition |
| [getNode](get-node.md) | [jvm]<br>abstract fun [getNode](get-node.md)(): [Node](../-node/index.md)<[T](../-action/index.md)><br>the node this Condition belongs to |
| [getPropensityContribution](get-propensity-contribution.md) | [jvm]<br>abstract fun [getPropensityContribution](get-propensity-contribution.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>This method is a support for the propensity calculation inside the Reactions. |
| [isValid](is-valid.md) | [jvm]<br>abstract fun [isValid](is-valid.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>true if the condition is satisfied in current environment. |
| [reactionReady](reaction-ready.md) | [jvm]<br>open fun [reactionReady](reaction-ready.md)()<br>This method is called by the [it.unibo.alchemist.core.interfaces.Simulation](../../it.unibo.alchemist.core.interfaces/-simulation/index.md) once the [Reaction](../-reaction/index.md) whose this [Condition](index.md) belongs to is the next one to be executed, and all its conditions passed (namely, the next operation will be the reaction execution). |

## Inheritors

| Name |
|---|
| [AbstractCondition](../../it.unibo.alchemist.model.implementations.conditions/-abstract-condition/index.md) |
| [ILsaCondition](../-i-lsa-condition/index.md) |
