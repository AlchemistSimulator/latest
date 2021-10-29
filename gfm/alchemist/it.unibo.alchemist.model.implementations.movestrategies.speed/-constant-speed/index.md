//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.movestrategies.speed](../index.md)/[ConstantSpeed](index.md)

# ConstantSpeed

[jvm]\
class [ConstantSpeed](index.md)<[P](index.md) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<[P](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.md)>?> : [SpeedSelectionStrategy](../../it.unibo.alchemist.model.interfaces.movestrategies/-speed-selection-strategy/index.md)<[P](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.md)> 

This strategy makes the node move at an average constant speed, which is influenced by the [it.unibo.alchemist.model.interfaces.TimeDistribution](../../it.unibo.alchemist.model.interfaces/-time-distribution/index.md) of the [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md) hosting this [it.unibo.alchemist.model.interfaces.Action](../../it.unibo.alchemist.model.interfaces/-action/index.md). This action tries to normalize on the [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md) rate, but if the [it.unibo.alchemist.model.interfaces.TimeDistribution](../../it.unibo.alchemist.model.interfaces/-time-distribution/index.md) has a high variance, the movements on the map will inherit this tract.

## Parameters

jvm

| | |
|---|---|
| <P> | Position type |

## Constructors

| | |
|---|---|
| [ConstantSpeed](-constant-speed.md) | [jvm]<br>open fun [ConstantSpeed](-constant-speed.md)(reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, speed: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>the reaction |

## Functions

| Name | Summary |
|---|---|
| [getNodeMovementLength](get-node-movement-length.md) | [jvm]<br>open fun [getNodeMovementLength](get-node-movement-length.md)(target: [P](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.md)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>the [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md) describing where the [it.unibo.alchemist.model.interfaces.Node](../../it.unibo.alchemist.model.interfaces/-node/index.md) is directed |
