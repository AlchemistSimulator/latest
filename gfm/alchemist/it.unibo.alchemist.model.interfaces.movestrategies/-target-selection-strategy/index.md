//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces.movestrategies](../index.md)/[TargetSelectionStrategy](index.md)

# TargetSelectionStrategy

[jvm]\
@[FunctionalInterface](https://docs.oracle.com/javase/8/docs/api/java/lang/FunctionalInterface.html)()

interface [TargetSelectionStrategy](index.md)<[P](index.md) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<out [P](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-constant-speed/index.md)>?> : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)

This interface models a strategy for selecting positions where to move.

## Parameters

jvm

| | |
|---|---|
| <P> | Position type |

## Functions

| Name | Summary |
|---|---|
| [getTarget](get-target.md) | [jvm]<br>abstract fun [getTarget](get-target.md)(): [P](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-constant-speed/index.md)<br>the next target where the [it.unibo.alchemist.model.interfaces.Node](../../it.unibo.alchemist.model.interfaces/-node/index.md) is directed |

## Inheritors

| Name |
|---|
| [ChangeTargetOnCollision](../../it.unibo.alchemist.model.implementations.movestrategies/-change-target-on-collision/index.md) |
| [FollowTarget](../../it.unibo.alchemist.model.implementations.movestrategies.target/-follow-target/index.md) |
| [FollowTrace](../../it.unibo.alchemist.model.implementations.movestrategies.target/-follow-trace/index.md) |
