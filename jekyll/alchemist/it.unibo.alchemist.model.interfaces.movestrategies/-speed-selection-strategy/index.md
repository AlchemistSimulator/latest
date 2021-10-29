---
title: SpeedSelectionStrategy
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces.movestrategies](../index.html)/[SpeedSelectionStrategy](index.html)



# SpeedSelectionStrategy



[jvm]\
@[FunctionalInterface](https://docs.oracle.com/javase/8/docs/api/java/lang/FunctionalInterface.html)()



interface [SpeedSelectionStrategy](index.html)<[P](index.html) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<out [P](../../it.unibo.alchemist.model.interfaces/-route/index.html)>?> : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)

Given the current target [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html), this strategy interface computes the current [it.unibo.alchemist.model.interfaces.Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)'s speed.



## Parameters


jvm

| | |
|---|---|
| <P> | position type |



## Functions


| Name | Summary |
|---|---|
| [getNodeMovementLength](get-node-movement-length.html) | [jvm]<br>abstract fun [getNodeMovementLength](get-node-movement-length.html)(target: [P](../../it.unibo.alchemist.model.interfaces/-route/index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>the [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html) describing where the [it.unibo.alchemist.model.interfaces.Node](../../it.unibo.alchemist.model.interfaces/-node/index.html) is directed |


## Inheritors


| Name |
|---|
| [InteractWithOthers](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-interact-with-others/index.html) |
| [ConstantSpace](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-constant-space/index.html) |
| [ConstantSpeed](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-constant-speed/index.html) |
| [GloballyConstantSpeed](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-globally-constant-speed/index.html) |
| [TraceDependantSpeed](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-trace-dependant-speed/index.html) |

