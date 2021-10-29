---
title: CellMove
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.actions](../index.html)/[CellMove](index.html)



# CellMove



[jvm]\
class [CellMove](index.html)<[P](index.html) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<[P](../../it.unibo.alchemist.model/-biochemistry-incarnation/index.html)>?> : [AbstractMoveNode](../-abstract-move-node/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html), [P](../../it.unibo.alchemist.model/-biochemistry-incarnation/index.html)>



## Parameters


jvm

| | |
|---|---|
| <P> | [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html) type |



## Constructors


| | |
|---|---|
| [CellMove](-cell-move.html) | [jvm]<br>open fun [CellMove](-cell-move.html)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html), [P](../../it.unibo.alchemist.model/-biochemistry-incarnation/index.html)>, node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>, inPercent: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), delta: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Initialize an Action that move the cell of a given space delta, which can be expressed in percent of the cell's diameter or in absolute. |


## Functions


| Name | Summary |
|---|---|
| [cloneAction](clone-action.html) | [jvm]<br>open fun [cloneAction](clone-action.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>): [CellMove](index.html)<[P](../../it.unibo.alchemist.model/-biochemistry-incarnation/index.html)> |
| [execute](execute.html) | [jvm]<br>open fun [execute](execute.html)() |
| [getContext](../-abstract-move-node/get-context.html) | [jvm]<br>fun [getContext](../-abstract-move-node/get-context.html)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.html) |
| [getNextPosition](get-next-position.html) | [jvm]<br>open fun [getNextPosition](get-next-position.html)(): [P](../../it.unibo.alchemist.model/-biochemistry-incarnation/index.html) |
| [getNode](get-node.html) | [jvm]<br>open fun [getNode](get-node.html)(): [CellNode](../../it.unibo.alchemist.model.interfaces/-cell-node/index.html)<[P](../../it.unibo.alchemist.model/-biochemistry-incarnation/index.html)> |
| [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.html) | [jvm]<br>fun [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.html)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)> |
| [toString](../-abstract-action/to-string.html) | [jvm]<br>open fun [toString](../-abstract-action/to-string.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |

