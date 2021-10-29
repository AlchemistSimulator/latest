//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.movestrategies.target](../index.md)/[FollowTarget](index.md)

# FollowTarget

[jvm]\
open class [FollowTarget](index.md)<[T](index.md), [P](index.md) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<[P](../../it.unibo.alchemist.model.interfaces/-route/index.md)>?> : [TargetSelectionStrategy](../../it.unibo.alchemist.model.interfaces.movestrategies/-target-selection-strategy/index.md)<[P](../../it.unibo.alchemist.model.interfaces/-route/index.md)> 

This strategy reads the value of a "target" molecule and tries to interpret it as a coordinate.

## Parameters

jvm

| | |
|---|---|
| <T> | Concentration type |

## Constructors

| | |
|---|---|
| [FollowTarget](-follow-target.md) | [jvm]<br>open fun [FollowTarget](-follow-target.md)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](index.md), [P](../../it.unibo.alchemist.model.interfaces/-route/index.md)>, node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>, targetMolecule: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md))<br>the environment |

## Functions

| Name | Summary |
|---|---|
| [getTarget](get-target.md) | [jvm]<br>fun [getTarget](get-target.md)(): [P](../../it.unibo.alchemist.model.interfaces/-route/index.md)<br>the next target where the [it.unibo.alchemist.model.interfaces.Node](../../it.unibo.alchemist.model.interfaces/-node/index.md) is directed |

## Inheritors

| Name |
|---|
| [FollowTargetOnMap](../-follow-target-on-map/index.md) |
