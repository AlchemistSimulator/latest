//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.actions](../index.md)/[AbstractMoveNode](index.md)

# AbstractMoveNode

[jvm]\
abstract class [AbstractMoveNode](index.md)<[T](index.md), [P](index.md) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<[P](../../it.unibo.alchemist/-supported-incarnations/get.md)>?> : [AbstractAction](../-abstract-action/index.md)<[T](../../it.unibo.alchemist/-supported-incarnations/get.md)> 

This action moves a node inside a given environment.

## Parameters

jvm

| | |
|---|---|
| <T> | concentration type |
| <P> | position type |

## Functions

| Name | Summary |
|---|---|
| [cloneAction](../../it.unibo.alchemist.model.interfaces/-action/clone-action.md) | [jvm]<br>abstract fun [cloneAction](../../it.unibo.alchemist.model.interfaces/-action/clone-action.md)(p: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist/-supported-incarnations/get.md)>, p1: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](../../it.unibo.alchemist/-supported-incarnations/get.md)>): [Action](../../it.unibo.alchemist.model.interfaces/-action/index.md)<[T](../../it.unibo.alchemist/-supported-incarnations/get.md)> |
| [execute](execute.md) | [jvm]<br>open fun [execute](execute.md)()<br>Detects if the move is in absolute or relative coordinates, then calls the correct method on the [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md). |
| [getContext](get-context.md) | [jvm]<br>fun [getContext](get-context.md)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.md) |
| [getNextPosition](get-next-position.md) | [jvm]<br>abstract fun [getNextPosition](get-next-position.md)(): [P](../../it.unibo.alchemist/-supported-incarnations/get.md)<br>The next position where to move, in absolute or relative coordinates depending on the value of isAbsolute. |
| [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.md) | [jvm]<br>fun [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.md)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.md)><br>How to override: if you intend your action to influence any reaction with compatible context, return null.<br>[jvm]<br>abstract fun [getOutboundDependencies](../../it.unibo.alchemist.model.interfaces/-action/get-outbound-dependencies.md)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.md)> |
| [toString](../-abstract-action/to-string.md) | [jvm]<br>open fun [toString](../-abstract-action/to-string.md)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |

## Inheritors

| Name |
|---|
| [AbstractSteeringAction](../-abstract-steering-action/index.md) |
| [AbstractConfigurableMoveNode](../-abstract-configurable-move-node/index.md) |
| [MoveForwardAndTeleport](../-move-forward-and-teleport/index.md) |
| [BrownianMove](../-brownian-move/index.md) |
| [CellMove](../-cell-move/index.md) |
