---
title: FollowTarget
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.movestrategies.target](../index.html)/[FollowTarget](index.html)



# FollowTarget



[jvm]\
open class [FollowTarget](index.html)<[T](index.html), [P](index.html) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<[P](../../it.unibo.alchemist/-supported-incarnations/get.html)>?> : [TargetSelectionStrategy](../../it.unibo.alchemist.model.interfaces.movestrategies/-target-selection-strategy/index.html)<[P](../../it.unibo.alchemist/-supported-incarnations/get.html)> 

This strategy reads the value of a "target" molecule and tries to interpret it as a coordinate.



## Parameters


jvm

| | |
|---|---|
| <T> | Concentration type |



## Constructors


| | |
|---|---|
| [FollowTarget](-follow-target.html) | [jvm]<br>open fun [FollowTarget](-follow-target.html)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../../it.unibo.alchemist/-supported-incarnations/get.html), [P](../../it.unibo.alchemist/-supported-incarnations/get.html)>, node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist/-supported-incarnations/get.html)>, targetMolecule: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html))<br>the environment |


## Functions


| Name | Summary |
|---|---|
| [getTarget](get-target.html) | [jvm]<br>fun [getTarget](get-target.html)(): [P](../../it.unibo.alchemist/-supported-incarnations/get.html)<br>the next target where the [it.unibo.alchemist.model.interfaces.Node](../../it.unibo.alchemist.model.interfaces/-node/index.html) is directed |


## Inheritors


| Name |
|---|
| [FollowTargetOnMap](../-follow-target-on-map/index.html) |

