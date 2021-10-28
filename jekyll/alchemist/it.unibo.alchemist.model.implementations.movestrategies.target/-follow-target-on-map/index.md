---
title: FollowTargetOnMap
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.movestrategies.target](../index.html)/[FollowTargetOnMap](index.html)



# FollowTargetOnMap



[jvm]\
open class [FollowTargetOnMap](index.html)<[T](index.html)> : [FollowTarget](../-follow-target/index.html)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.html), [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)> 

This strategy reads the value of a "target" molecule and tries to interpret it as a coordinate.



## Parameters


jvm

| | |
|---|---|
| <T> | concentration type |



## Constructors


| | |
|---|---|
| [FollowTargetOnMap](-follow-target-on-map.html) | [jvm]<br>open fun [FollowTargetOnMap](-follow-target-on-map.html)(env: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.html), [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)>, n: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.html)>, targetMolecule: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html))<br>the environment |


## Functions


| Name | Summary |
|---|---|
| [getTarget](../-follow-target/get-target.html) | [jvm]<br>fun [getTarget](../-follow-target/get-target.html)(): [P](../../it.unibo.alchemist.model.implementations.movestrategies.routing/-ignore-streets/index.html) |

