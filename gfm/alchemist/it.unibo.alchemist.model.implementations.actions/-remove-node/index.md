//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.actions](../index.md)/[RemoveNode](index.md)

# RemoveNode

[jvm]\
class [RemoveNode](index.md)<[T](index.md)> : [AbstractAction](../-abstract-action/index.md)<[T](../../it.unibo.alchemist.model.implementations.timedistributions/-weibull-distributed-weibull-time/index.md)> 

Removes the current node from the environment.

## Parameters

jvm

| | |
|---|---|
| <T> | concentration type |

## Constructors

| | |
|---|---|
| [RemoveNode](-remove-node.md) | [jvm]<br>open fun [RemoveNode](-remove-node.md)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](../../it.unibo.alchemist.model.implementations.timedistributions/-weibull-distributed-weibull-time/index.md), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.timedistributions/-weibull-distributed-weibull-time/index.md)>)<br>the current environment |

## Functions

| Name | Summary |
|---|---|
| [cloneAction](clone-action.md) | [jvm]<br>open fun [cloneAction](clone-action.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.timedistributions/-weibull-distributed-weibull-time/index.md)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](../../it.unibo.alchemist.model.implementations.timedistributions/-weibull-distributed-weibull-time/index.md)>): [RemoveNode](index.md)<[T](../../it.unibo.alchemist.model.implementations.timedistributions/-weibull-distributed-weibull-time/index.md)> |
| [execute](execute.md) | [jvm]<br>open fun [execute](execute.md)() |
| [getContext](get-context.md) | [jvm]<br>open fun [getContext](get-context.md)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.md) |
| [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.md) | [jvm]<br>fun [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.md)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.md)><br>How to override: if you intend your action to influence any reaction with compatible context, return null.<br>[jvm]<br>abstract fun [getOutboundDependencies](../../it.unibo.alchemist.model.interfaces/-action/get-outbound-dependencies.md)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.md)> |
| [toString](to-string.md) | [jvm]<br>open fun [toString](to-string.md)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |
