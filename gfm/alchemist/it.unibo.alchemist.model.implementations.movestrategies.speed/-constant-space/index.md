//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.movestrategies.speed](../index.md)/[ConstantSpace](index.md)

# ConstantSpace

[jvm]\
class [ConstantSpace](index.md)<[P](index.md) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<[P](../../it.unibo.alchemist/-supported-incarnations/get.md)>?> : [SpeedSelectionStrategy](../../it.unibo.alchemist.model.interfaces.movestrategies/-speed-selection-strategy/index.md)<[P](../../it.unibo.alchemist/-supported-incarnations/get.md)> 

This strategy makes the node move every time of a fixed amount of space.

## Parameters

jvm

| | |
|---|---|
| <P> | Position type |

## Constructors

| | |
|---|---|
| [ConstantSpace](-constant-space.md) | [jvm]<br>open fun [ConstantSpace](-constant-space.md)(step: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>the step length (in meters, or the unit you are using in your simulation) |

## Functions

| Name | Summary |
|---|---|
| [getNodeMovementLength](get-node-movement-length.md) | [jvm]<br>open fun [getNodeMovementLength](get-node-movement-length.md)(target: [P](../../it.unibo.alchemist/-supported-incarnations/get.md)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>the [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md) describing where the [it.unibo.alchemist.model.interfaces.Node](../../it.unibo.alchemist.model.interfaces/-node/index.md) is directed |
