---
title: BrownianMove
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.actions](../index.html)/[BrownianMove](index.html)



# BrownianMove



[jvm]\
class [BrownianMove](index.html)<[T](index.html), [P](index.html) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<[P](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html)>?> : [AbstractMoveNode](../-abstract-move-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html), [P](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html)> 

Moves the node randomly.



## Parameters


jvm

| | |
|---|---|
| <T> | Concentration type |
| <P> | [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html) type |



## Constructors


| | |
|---|---|
| [BrownianMove](-brownian-move.html) | [jvm]<br>open fun [BrownianMove](-brownian-move.html)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html), [P](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html)>, node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html)>, randomGenerator: RandomGenerator, range: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>the environment |


## Functions


| Name | Summary |
|---|---|
| [cloneAction](clone-action.html) | [jvm]<br>open fun [cloneAction](clone-action.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html)>): [Action](../../it.unibo.alchemist.model.interfaces/-action/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html)> |
| [execute](../-abstract-move-node/execute.html) | [jvm]<br>open fun [execute](../-abstract-move-node/execute.html)()<br>Detects if the move is in absolute or relative coordinates, then calls the correct method on the [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html).<br>[jvm]<br>abstract fun [execute](../../it.unibo.alchemist.model.interfaces/-action/execute.html)() |
| [getContext](../-abstract-move-node/get-context.html) | [jvm]<br>fun [getContext](../-abstract-move-node/get-context.html)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.html)<br>abstract fun [getContext](../../it.unibo.alchemist.model.interfaces/-action/get-context.html)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.html) |
| [getNextPosition](get-next-position.html) | [jvm]<br>open fun [getNextPosition](get-next-position.html)(): [P](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html)<br>The next position where to move, in absolute or relative coordinates depending on the value of isAbsolute. |
| [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.html) | [jvm]<br>fun [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.html)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)><br>How to override: if you intend your action to influence any reaction with compatible context, return null.<br>[jvm]<br>abstract fun [getOutboundDependencies](../../it.unibo.alchemist.model.interfaces/-action/get-outbound-dependencies.html)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)> |
| [toString](../-abstract-action/to-string.html) | [jvm]<br>open fun [toString](../-abstract-action/to-string.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |

