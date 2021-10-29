//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces.movestrategies](../index.md)/[SpeedSelectionStrategy](index.md)

# SpeedSelectionStrategy

[jvm]\
@[FunctionalInterface](https://docs.oracle.com/javase/8/docs/api/java/lang/FunctionalInterface.html)()

interface [SpeedSelectionStrategy](index.md)<[P](index.md) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<out [P](../../it.unibo.alchemist.model.interfaces/-route/index.md)>?> : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)

Given the current target [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md), this strategy interface computes the current [it.unibo.alchemist.model.interfaces.Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)'s speed.

## Parameters

jvm

| | |
|---|---|
| <P> | position type |

## Functions

| Name | Summary |
|---|---|
| [getNodeMovementLength](get-node-movement-length.md) | [jvm]<br>abstract fun [getNodeMovementLength](get-node-movement-length.md)(target: [P](../../it.unibo.alchemist.model.interfaces/-route/index.md)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>the [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md) describing where the [it.unibo.alchemist.model.interfaces.Node](../../it.unibo.alchemist.model.interfaces/-node/index.md) is directed |

## Inheritors

| Name |
|---|
| [InteractWithOthers](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-interact-with-others/index.md) |
| [ConstantSpace](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-constant-space/index.md) |
| [ConstantSpeed](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-constant-speed/index.md) |
| [GloballyConstantSpeed](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-globally-constant-speed/index.md) |
| [TraceDependantSpeed](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-trace-dependant-speed/index.md) |
