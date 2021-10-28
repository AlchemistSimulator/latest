//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.movestrategies.speed](../index.md)/[GloballyConstantSpeed](index.md)

# GloballyConstantSpeed

[jvm]\
class [GloballyConstantSpeed](index.md)<[P](index.md) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<[P](index.md)>>(**reaction**: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<*>, **maxSpeed**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) : [SpeedSelectionStrategy](../../it.unibo.alchemist.model.interfaces.movestrategies/-speed-selection-strategy/index.md)<[P](index.md)> 

Similar to [ConstantSpeed](../-constant-speed/index.md) but takes in consideration the time distribution's rate instead of the reaction's rate.

## Constructors

| | |
|---|---|
| [GloballyConstantSpeed](-globally-constant-speed.md) | [jvm]<br>fun [GloballyConstantSpeed](-globally-constant-speed.md)(reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<*>, maxSpeed: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) |

## Functions

| Name | Summary |
|---|---|
| [getNodeMovementLength](get-node-movement-length.md) | [jvm]<br>open override fun [getNodeMovementLength](get-node-movement-length.md)(target: [P](index.md)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>the [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md) describing where the [it.unibo.alchemist.model.interfaces.Node](../../it.unibo.alchemist.model.interfaces/-node/index.md) is directed |
