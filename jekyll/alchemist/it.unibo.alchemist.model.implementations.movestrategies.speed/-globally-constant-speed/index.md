---
title: GloballyConstantSpeed
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.movestrategies.speed](../index.html)/[GloballyConstantSpeed](index.html)



# GloballyConstantSpeed



[jvm]\
class [GloballyConstantSpeed](index.html)<[P](index.html) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<[P](index.html)>>(**reaction**: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<*>, **maxSpeed**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) : [SpeedSelectionStrategy](../../it.unibo.alchemist.model.interfaces.movestrategies/-speed-selection-strategy/index.html)<[P](index.html)> 

Similar to [ConstantSpeed](../-constant-speed/index.html) but takes in consideration the time distribution's rate instead of the reaction's rate.



## Constructors


| | |
|---|---|
| [GloballyConstantSpeed](-globally-constant-speed.html) | [jvm]<br>fun [GloballyConstantSpeed](-globally-constant-speed.html)(reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<*>, maxSpeed: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) |


## Functions


| Name | Summary |
|---|---|
| [getNodeMovementLength](get-node-movement-length.html) | [jvm]<br>open override fun [getNodeMovementLength](get-node-movement-length.html)(target: [P](index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>the [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html) describing where the [it.unibo.alchemist.model.interfaces.Node](../../it.unibo.alchemist.model.interfaces/-node/index.html) is directed |

