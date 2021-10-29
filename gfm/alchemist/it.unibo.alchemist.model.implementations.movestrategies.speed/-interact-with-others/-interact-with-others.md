//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.movestrategies.speed](../index.md)/[InteractWithOthers](index.md)/[InteractWithOthers](-interact-with-others.md)

# InteractWithOthers

[jvm]\
open fun [InteractWithOthers](-interact-with-others.md)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](../../it.unibo.alchemist/-supported-incarnations/get.md), [P](../../it.unibo.alchemist/-supported-incarnations/get.md)>, n: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist/-supported-incarnations/get.md)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](../../it.unibo.alchemist/-supported-incarnations/get.md)>, inter: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md), speed: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), radius: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), interaction: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))

## Parameters

jvm

| | |
|---|---|
| environment | the environment |
| n | the node |
| reaction | the reaction |
| inter | the molecule that identifies an interacting node |
| speed | the normal speed of the node |
| radius | the radius where to search for interacting nodes |
| interaction | the interaction factor. This will be multiplied by a crowd factor dynamically computed, and the speed will be divided by the number obtained |
