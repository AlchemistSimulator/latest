//[alchemist](../../index.md)/[it.unibo.alchemist.model.implementations.actions](index.md)/[toPositions](to-positions.md)

# toPositions

[jvm]\
fun <[P](to-positions.md) : [Position](../it.unibo.alchemist.model.interfaces/-position/index.md)<[P](to-positions.md)>> [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<out [Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html)>.[toPositions](to-positions.md)(environment: [Environment](../it.unibo.alchemist.model.interfaces/-environment/index.md)<*, [P](to-positions.md)>): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[P](to-positions.md)>

Converts an array of numbers representing positions to an actual list of positions. E.g. the array 2,3,4,5 in a bidimensional environment would be transformed into a list containing positions (2,3) and (4,5).
