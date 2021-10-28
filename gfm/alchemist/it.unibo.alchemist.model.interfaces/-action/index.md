//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces](../index.md)/[Action](index.md)

# Action

[jvm]\
interface [Action](index.md)<[T](index.md)> : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)

## Parameters

jvm

| | |
|---|---|
| <T> | The type which describes the concentration of a molecule The interface of an action. Every action must implement this interface. |

## Functions

| Name | Summary |
|---|---|
| [cloneAction](clone-action.md) | [jvm]<br>abstract fun [cloneAction](clone-action.md)(node: [Node](../-node/index.md)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.md)>, reaction: [Reaction](../-reaction/index.md)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.md)>): [Action](index.md)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.md)><br>This method allows to clone this action on a new node. |
| [execute](execute.md) | [jvm]<br>abstract fun [execute](execute.md)()<br>Effectively executes this action. |
| [getContext](get-context.md) | [jvm]<br>abstract fun [getContext](get-context.md)(): [Context](../-context/index.md)<br>The context for this action. |
| [getOutboundDependencies](get-outbound-dependencies.md) | [jvm]<br>abstract fun [getOutboundDependencies](get-outbound-dependencies.md)(): ListSet<out [Dependency](../-dependency/index.md)><br>The list of the dependencies that this action generates. |

## Inheritors

| Name |
|---|
| [SteeringAction](../-steering-action/index.md) |
| [AbstractAction](../../it.unibo.alchemist.model.implementations.actions/-abstract-action/index.md) |
| [RunProtelisProgram](../../it.unibo.alchemist.model.implementations.actions/-run-protelis-program/index.md) |
| [ILsaAction](../-i-lsa-action/index.md) |
