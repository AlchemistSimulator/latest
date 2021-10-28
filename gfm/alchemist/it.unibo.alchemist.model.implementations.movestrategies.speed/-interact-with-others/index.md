//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.movestrategies.speed](../index.md)/[InteractWithOthers](index.md)

# InteractWithOthers

[jvm]\
class [InteractWithOthers](index.md)<[T](index.md), [P](index.md) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<out [P](../-constant-speed/index.md)>?> : [SpeedSelectionStrategy](../../it.unibo.alchemist.model.interfaces.movestrategies/-speed-selection-strategy/index.md)<[P](../-constant-speed/index.md)> 

This strategy slows down nodes depending on how many "interacting" nodes are found in the surroundings. It is an attempt at modeling crowding slow-downs.

## Parameters

jvm

| | |
|---|---|
| <P> | position type |
| <T> | concentration type |

## Constructors

| | |
|---|---|
| [InteractWithOthers](-interact-with-others.md) | [jvm]<br>open fun [InteractWithOthers](-interact-with-others.md)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](index.md), [P](../-constant-speed/index.md)>, n: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](index.md)>, inter: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md), speed: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), radius: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), interaction: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>the environment |

## Functions

| Name | Summary |
|---|---|
| [getNodeMovementLength](get-node-movement-length.md) | [jvm]<br>open fun [getNodeMovementLength](get-node-movement-length.md)(target: [P](../-constant-speed/index.md)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>the [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md) describing where the [it.unibo.alchemist.model.interfaces.Node](../../it.unibo.alchemist.model.interfaces/-node/index.md) is directed |
