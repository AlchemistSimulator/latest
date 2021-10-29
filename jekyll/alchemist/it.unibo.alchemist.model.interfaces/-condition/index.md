---
title: Condition
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces](../index.html)/[Condition](index.html)



# Condition



[jvm]\
interface [Condition](index.html)<[T](index.html)> : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)



## Parameters


jvm

| | |
|---|---|
| <T> | The type which describes the concentration of a molecule Interface of a condition. Every condition must implement this interface. |



## Functions


| Name | Summary |
|---|---|
| [cloneCondition](clone-condition.html) | [jvm]<br>abstract fun [cloneCondition](clone-condition.html)(node: [Node](../-node/index.html)<[T](../-node/index.html)>, reaction: [Reaction](../-reaction/index.html)<[T](../-node/index.html)>): [Condition](index.html)<[T](../-node/index.html)><br>This method allows to clone this action on a new node. |
| [getContext](get-context.html) | [jvm]<br>abstract fun [getContext](get-context.html)(): [Context](../-context/index.html)<br>The context for this condition. |
| [getInboundDependencies](get-inbound-dependencies.html) | [jvm]<br>abstract fun [getInboundDependencies](get-inbound-dependencies.html)(): ListSet<out [Dependency](../-dependency/index.html)><br>The list of molecules whose concentration may influence the truth value of this condition |
| [getNode](get-node.html) | [jvm]<br>abstract fun [getNode](get-node.html)(): [Node](../-node/index.html)<[T](../-node/index.html)><br>the node this Condition belongs to |
| [getPropensityContribution](get-propensity-contribution.html) | [jvm]<br>abstract fun [getPropensityContribution](get-propensity-contribution.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>This method is a support for the propensity calculation inside the Reactions. |
| [isValid](is-valid.html) | [jvm]<br>abstract fun [isValid](is-valid.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>true if the condition is satisfied in current environment. |
| [reactionReady](reaction-ready.html) | [jvm]<br>open fun [reactionReady](reaction-ready.html)()<br>This method is called by the [it.unibo.alchemist.core.interfaces.Simulation](../../it.unibo.alchemist.core.interfaces/-simulation/index.html) once the [Reaction](../-reaction/index.html) whose this [Condition](index.html) belongs to is the next one to be executed, and all its conditions passed (namely, the next operation will be the reaction execution). |


## Inheritors


| Name |
|---|
| [AbstractCondition](../../it.unibo.alchemist.model.implementations.conditions/-abstract-condition/index.html) |
| [ILsaCondition](../-i-lsa-condition/index.html) |

