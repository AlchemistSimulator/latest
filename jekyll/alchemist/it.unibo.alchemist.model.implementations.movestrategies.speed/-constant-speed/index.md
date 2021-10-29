---
title: ConstantSpeed
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.movestrategies.speed](../index.html)/[ConstantSpeed](index.html)



# ConstantSpeed



[jvm]\
class [ConstantSpeed](index.html)<[P](index.html) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<[P](../../it.unibo.alchemist.model.interfaces/-route/index.html)>?> : [SpeedSelectionStrategy](../../it.unibo.alchemist.model.interfaces.movestrategies/-speed-selection-strategy/index.html)<[P](../../it.unibo.alchemist.model.interfaces/-route/index.html)> 

This strategy makes the node move at an average constant speed, which is influenced by the [it.unibo.alchemist.model.interfaces.TimeDistribution](../../it.unibo.alchemist.model.interfaces/-time-distribution/index.html) of the [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html) hosting this [it.unibo.alchemist.model.interfaces.Action](../../it.unibo.alchemist.model.interfaces/-action/index.html). This action tries to normalize on the [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html) rate, but if the [it.unibo.alchemist.model.interfaces.TimeDistribution](../../it.unibo.alchemist.model.interfaces/-time-distribution/index.html) has a high variance, the movements on the map will inherit this tract.



## Parameters


jvm

| | |
|---|---|
| <P> | Position type |



## Constructors


| | |
|---|---|
| [ConstantSpeed](-constant-speed.html) | [jvm]<br>open fun [ConstantSpeed](-constant-speed.html)(reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, speed: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>the reaction |


## Functions


| Name | Summary |
|---|---|
| [getNodeMovementLength](get-node-movement-length.html) | [jvm]<br>open fun [getNodeMovementLength](get-node-movement-length.html)(target: [P](../../it.unibo.alchemist.model.interfaces/-route/index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>the [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html) describing where the [it.unibo.alchemist.model.interfaces.Node](../../it.unibo.alchemist.model.interfaces/-node/index.html) is directed |

