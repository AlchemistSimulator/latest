---
title: Action
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces](../index.html)/[Action](index.html)



# Action



[jvm]\
interface [Action](index.html)<[T](index.html)> : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)



## Parameters


jvm

| | |
|---|---|
| <T> | The type which describes the concentration of a molecule The interface of an action. Every action must implement this interface. |



## Functions


| Name | Summary |
|---|---|
| [cloneAction](clone-action.html) | [jvm]<br>abstract fun [cloneAction](clone-action.html)(node: [Node](../-node/index.html)<[T](../-node/index.html)>, reaction: [Reaction](../-reaction/index.html)<[T](../-node/index.html)>): [Action](index.html)<[T](../-node/index.html)><br>This method allows to clone this action on a new node. |
| [execute](execute.html) | [jvm]<br>abstract fun [execute](execute.html)()<br>Effectively executes this action. |
| [getContext](get-context.html) | [jvm]<br>abstract fun [getContext](get-context.html)(): [Context](../-context/index.html)<br>The context for this action. |
| [getOutboundDependencies](get-outbound-dependencies.html) | [jvm]<br>abstract fun [getOutboundDependencies](get-outbound-dependencies.html)(): ListSet<out [Dependency](../-dependency/index.html)><br>The list of the dependencies that this action generates. |


## Inheritors


| Name |
|---|
| [SteeringAction](../-steering-action/index.html) |
| [AbstractAction](../../it.unibo.alchemist.model.implementations.actions/-abstract-action/index.html) |
| [RunProtelisProgram](../../it.unibo.alchemist.model.implementations.actions/-run-protelis-program/index.html) |
| [ILsaAction](../-i-lsa-action/index.html) |

