---
title: TargetSelectionStrategy
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces.movestrategies](../index.html)/[TargetSelectionStrategy](index.html)



# TargetSelectionStrategy



[jvm]\
@[FunctionalInterface](https://docs.oracle.com/javase/8/docs/api/java/lang/FunctionalInterface.html)()



interface [TargetSelectionStrategy](index.html)<[P](index.html) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<out [P](../../it.unibo.alchemist/-supported-incarnations/get.html)>?> : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)

This interface models a strategy for selecting positions where to move.



## Parameters


jvm

| | |
|---|---|
| <P> | Position type |



## Functions


| Name | Summary |
|---|---|
| [getTarget](get-target.html) | [jvm]<br>abstract fun [getTarget](get-target.html)(): [P](../../it.unibo.alchemist/-supported-incarnations/get.html)<br>the next target where the [it.unibo.alchemist.model.interfaces.Node](../../it.unibo.alchemist.model.interfaces/-node/index.html) is directed |


## Inheritors


| Name |
|---|
| [ChangeTargetOnCollision](../../it.unibo.alchemist.model.implementations.movestrategies/-change-target-on-collision/index.html) |
| [FollowTarget](../../it.unibo.alchemist.model.implementations.movestrategies.target/-follow-target/index.html) |
| [FollowTrace](../../it.unibo.alchemist.model.implementations.movestrategies.target/-follow-trace/index.html) |

