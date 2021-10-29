//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.movestrategies.target](../index.md)/[FollowTargetOnMap](index.md)

# FollowTargetOnMap

[jvm]\
open class [FollowTargetOnMap](index.md)<[T](index.md)> : [FollowTarget](../-follow-target/index.md)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.md), [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md)> 

This strategy reads the value of a "target" molecule and tries to interpret it as a coordinate.

## Parameters

jvm

| | |
|---|---|
| <T> | concentration type |

## Constructors

| | |
|---|---|
| [FollowTargetOnMap](-follow-target-on-map.md) | [jvm]<br>open fun [FollowTargetOnMap](-follow-target-on-map.md)(env: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.md), [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md)>, n: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.md)>, targetMolecule: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md))<br>the environment |

## Functions

| Name | Summary |
|---|---|
| [getTarget](../-follow-target/get-target.md) | [jvm]<br>fun [getTarget](../-follow-target/get-target.md)(): [P](../../it.unibo.alchemist.loader.deployments/-deployment/index.md) |
