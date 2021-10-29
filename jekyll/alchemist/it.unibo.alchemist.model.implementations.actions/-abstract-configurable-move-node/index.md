---
title: AbstractConfigurableMoveNode
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.actions](../index.html)/[AbstractConfigurableMoveNode](index.html)



# AbstractConfigurableMoveNode



[jvm]\
abstract class [AbstractConfigurableMoveNode](index.html)<[T](index.html), [P](index.html) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<[P](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)>?> : [AbstractMoveNode](../-abstract-move-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html), [P](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)> 

An abstract class that factorizes code for multiple different movements. With three strategies can be defined: the next target to be reached, the routing strategy to adopt, the speed to move at.



## Parameters


jvm

| | |
|---|---|
| <T> | Concentration type |
| <P> | [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html) type |



## Functions


| Name | Summary |
|---|---|
| [cloneAction](../../it.unibo.alchemist.model.interfaces/-action/clone-action.html) | [jvm]<br>abstract fun [cloneAction](../../it.unibo.alchemist.model.interfaces/-action/clone-action.html)(p: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)>, p1: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)>): [Action](../../it.unibo.alchemist.model.interfaces/-action/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)> |
| [execute](../-abstract-move-node/execute.html) | [jvm]<br>open fun [execute](../-abstract-move-node/execute.html)()<br>Detects if the move is in absolute or relative coordinates, then calls the correct method on the [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html).<br>[jvm]<br>abstract fun [execute](../../it.unibo.alchemist.model.interfaces/-action/execute.html)() |
| [getContext](../-abstract-move-node/get-context.html) | [jvm]<br>fun [getContext](../-abstract-move-node/get-context.html)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.html)<br>abstract fun [getContext](../../it.unibo.alchemist.model.interfaces/-action/get-context.html)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.html) |
| [getNextPosition](get-next-position.html) | [jvm]<br>fun [getNextPosition](get-next-position.html)(): [P](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)<br>The next position where to move, in absolute or relative coordinates depending on the value of isAbsolute. |
| [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.html) | [jvm]<br>fun [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.html)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)><br>How to override: if you intend your action to influence any reaction with compatible context, return null.<br>[jvm]<br>abstract fun [getOutboundDependencies](../../it.unibo.alchemist.model.interfaces/-action/get-outbound-dependencies.html)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)> |
| [toString](../-abstract-action/to-string.html) | [jvm]<br>open fun [toString](../-abstract-action/to-string.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |


## Inheritors


| Name |
|---|
| [AbstractEuclideanConfigurableMoveNode](../-abstract-euclidean-configurable-move-node/index.html) |
| [MoveToTarget](../-move-to-target/index.html) |
| [MoveOnMap](../-move-on-map/index.html) |

