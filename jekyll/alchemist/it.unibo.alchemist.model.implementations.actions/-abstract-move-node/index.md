---
title: AbstractMoveNode
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.actions](../index.html)/[AbstractMoveNode](index.html)



# AbstractMoveNode



[jvm]\
abstract class [AbstractMoveNode](index.html)<[T](index.html), [P](index.html) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<[P](../../it.unibo.alchemist/-supported-incarnations/get.html)>?> : [AbstractAction](../-abstract-action/index.html)<[T](../../it.unibo.alchemist/-supported-incarnations/get.html)> 

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
| [cloneAction](../../it.unibo.alchemist.model.interfaces/-action/clone-action.html) | [jvm]<br>abstract fun [cloneAction](../../it.unibo.alchemist.model.interfaces/-action/clone-action.html)(p: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist/-supported-incarnations/get.html)>, p1: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist/-supported-incarnations/get.html)>): [Action](../../it.unibo.alchemist.model.interfaces/-action/index.html)<[T](../../it.unibo.alchemist/-supported-incarnations/get.html)> |
| [execute](execute.html) | [jvm]<br>open fun [execute](execute.html)()<br>Detects if the move is in absolute or relative coordinates, then calls the correct method on the [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html). |
| [getContext](get-context.html) | [jvm]<br>fun [getContext](get-context.html)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.html) |
| [getNextPosition](get-next-position.html) | [jvm]<br>abstract fun [getNextPosition](get-next-position.html)(): [P](../../it.unibo.alchemist/-supported-incarnations/get.html)<br>The next position where to move, in absolute or relative coordinates depending on the value of isAbsolute. |
| [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.html) | [jvm]<br>fun [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.html)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)><br>How to override: if you intend your action to influence any reaction with compatible context, return null.<br>[jvm]<br>abstract fun [getOutboundDependencies](../../it.unibo.alchemist.model.interfaces/-action/get-outbound-dependencies.html)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)> |
| [toString](../-abstract-action/to-string.html) | [jvm]<br>open fun [toString](../-abstract-action/to-string.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |


## Inheritors


| Name |
|---|
| [AbstractSteeringAction](../-abstract-steering-action/index.html) |
| [AbstractConfigurableMoveNode](../-abstract-configurable-move-node/index.html) |
| [MoveForwardAndTeleport](../-move-forward-and-teleport/index.html) |
| [BrownianMove](../-brownian-move/index.html) |
| [CellMove](../-cell-move/index.html) |

