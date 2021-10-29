---
title: ConstantSpace
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.movestrategies.speed](../index.html)/[ConstantSpace](index.html)



# ConstantSpace



[jvm]\
class [ConstantSpace](index.html)<[P](index.html) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<[P](../../it.unibo.alchemist.model.interfaces/-route/index.html)>?> : [SpeedSelectionStrategy](../../it.unibo.alchemist.model.interfaces.movestrategies/-speed-selection-strategy/index.html)<[P](../../it.unibo.alchemist.model.interfaces/-route/index.html)> 

This strategy makes the node move every time of a fixed amount of space.



## Parameters


jvm

| | |
|---|---|
| <P> | Position type |



## Constructors


| | |
|---|---|
| [ConstantSpace](-constant-space.html) | [jvm]<br>open fun [ConstantSpace](-constant-space.html)(step: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>the step length (in meters, or the unit you are using in your simulation) |


## Functions


| Name | Summary |
|---|---|
| [getNodeMovementLength](get-node-movement-length.html) | [jvm]<br>open fun [getNodeMovementLength](get-node-movement-length.html)(target: [P](../../it.unibo.alchemist.model.interfaces/-route/index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>the [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html) describing where the [it.unibo.alchemist.model.interfaces.Node](../../it.unibo.alchemist.model.interfaces/-node/index.html) is directed |

