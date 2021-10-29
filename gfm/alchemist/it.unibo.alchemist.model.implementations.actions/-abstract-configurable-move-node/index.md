//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.actions](../index.md)/[AbstractConfigurableMoveNode](index.md)

# AbstractConfigurableMoveNode

[jvm]\
abstract class [AbstractConfigurableMoveNode](index.md)<[T](index.md), [P](index.md) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<[P](../../it.unibo.alchemist/-supported-incarnations/get.md)>?> : [AbstractMoveNode](../-abstract-move-node/index.md)<[T](../../it.unibo.alchemist/-supported-incarnations/get.md), [P](../../it.unibo.alchemist/-supported-incarnations/get.md)> 

An abstract class that factorizes code for multiple different movements. With three strategies can be defined: the next target to be reached, the routing strategy to adopt, the speed to move at.

## Parameters

jvm

| | |
|---|---|
| <T> | Concentration type |
| <P> | [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md) type |

## Functions

| Name | Summary |
|---|---|
| [cloneAction](../../it.unibo.alchemist.model.interfaces/-action/clone-action.md) | [jvm]<br>abstract fun [cloneAction](../../it.unibo.alchemist.model.interfaces/-action/clone-action.md)(p: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist/-supported-incarnations/get.md)>, p1: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](../../it.unibo.alchemist/-supported-incarnations/get.md)>): [Action](../../it.unibo.alchemist.model.interfaces/-action/index.md)<[T](../../it.unibo.alchemist/-supported-incarnations/get.md)> |
| [execute](../-abstract-move-node/execute.md) | [jvm]<br>open fun [execute](../-abstract-move-node/execute.md)()<br>Detects if the move is in absolute or relative coordinates, then calls the correct method on the [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md).<br>[jvm]<br>abstract fun [execute](../../it.unibo.alchemist.model.interfaces/-action/execute.md)() |
| [getContext](../-abstract-move-node/get-context.md) | [jvm]<br>fun [getContext](../-abstract-move-node/get-context.md)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.md)<br>abstract fun [getContext](../../it.unibo.alchemist.model.interfaces/-action/get-context.md)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.md) |
| [getNextPosition](get-next-position.md) | [jvm]<br>fun [getNextPosition](get-next-position.md)(): [P](../../it.unibo.alchemist/-supported-incarnations/get.md)<br>The next position where to move, in absolute or relative coordinates depending on the value of isAbsolute. |
| [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.md) | [jvm]<br>fun [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.md)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.md)><br>How to override: if you intend your action to influence any reaction with compatible context, return null.<br>[jvm]<br>abstract fun [getOutboundDependencies](../../it.unibo.alchemist.model.interfaces/-action/get-outbound-dependencies.md)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.md)> |
| [toString](../-abstract-action/to-string.md) | [jvm]<br>open fun [toString](../-abstract-action/to-string.md)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |

## Inheritors

| Name |
|---|
| [AbstractEuclideanConfigurableMoveNode](../-abstract-euclidean-configurable-move-node/index.md) |
| [MoveToTarget](../-move-to-target/index.md) |
| [MoveOnMap](../-move-on-map/index.md) |
