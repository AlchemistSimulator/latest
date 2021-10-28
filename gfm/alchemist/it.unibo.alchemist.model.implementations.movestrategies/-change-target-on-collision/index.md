//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.movestrategies](../index.md)/[ChangeTargetOnCollision](index.md)

# ChangeTargetOnCollision

[jvm]\
abstract class [ChangeTargetOnCollision](index.md)<[P](index.md) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<[P](index.md)>>(**getCurrentPosition**: () -> [P](index.md)) : [TargetSelectionStrategy](../../it.unibo.alchemist.model.interfaces.movestrategies/-target-selection-strategy/index.md)<[P](index.md)> 

Base class for [TargetSelectionStrategy](../../it.unibo.alchemist.model.interfaces.movestrategies/-target-selection-strategy/index.md) offering automatic target change on collision and utilities for initialization. getCurrentPosition should return the current position of the object to move. [P](index.md) is the position type to use.

## Constructors

| | |
|---|---|
| [ChangeTargetOnCollision](-change-target-on-collision.md) | [jvm]<br>fun <[P](index.md) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<[P](index.md)>> [ChangeTargetOnCollision](-change-target-on-collision.md)(getCurrentPosition: () -> [P](index.md)) |

## Functions

| Name | Summary |
|---|---|
| [getTarget](get-target.md) | [jvm]<br>open override fun [getTarget](get-target.md)(): [P](index.md)<br>the next target where the [it.unibo.alchemist.model.interfaces.Node](../../it.unibo.alchemist.model.interfaces/-node/index.md) is directed |

## Inheritors

| Name |
|---|
| [RandomTarget](../-random-target/index.md) |
