---
title: ChangeTargetOnCollision
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.movestrategies](../index.html)/[ChangeTargetOnCollision](index.html)



# ChangeTargetOnCollision



[jvm]\
abstract class [ChangeTargetOnCollision](index.html)<[P](index.html) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<[P](index.html)>>(**getCurrentPosition**: () -> [P](index.html)) : [TargetSelectionStrategy](../../it.unibo.alchemist.model.interfaces.movestrategies/-target-selection-strategy/index.html)<[P](index.html)> 

Base class for [TargetSelectionStrategy](../../it.unibo.alchemist.model.interfaces.movestrategies/-target-selection-strategy/index.html) offering automatic target change on collision and utilities for initialization. getCurrentPosition should return the current position of the object to move. [P](index.html) is the position type to use.



## Constructors


| | |
|---|---|
| [ChangeTargetOnCollision](-change-target-on-collision.html) | [jvm]<br>fun <[P](index.html) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<[P](index.html)>> [ChangeTargetOnCollision](-change-target-on-collision.html)(getCurrentPosition: () -> [P](index.html)) |


## Functions


| Name | Summary |
|---|---|
| [getTarget](get-target.html) | [jvm]<br>open override fun [getTarget](get-target.html)(): [P](index.html)<br>the next target where the [it.unibo.alchemist.model.interfaces.Node](../../it.unibo.alchemist.model.interfaces/-node/index.html) is directed |


## Inheritors


| Name |
|---|
| [RandomTarget](../-random-target/index.html) |

