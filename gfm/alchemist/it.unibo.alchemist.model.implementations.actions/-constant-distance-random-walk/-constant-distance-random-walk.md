//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.actions](../index.md)/[ConstantDistanceRandomWalk](index.md)/[ConstantDistanceRandomWalk](-constant-distance-random-walk.md)

# ConstantDistanceRandomWalk

[jvm]\
fun <[T](index.md)> [ConstantDistanceRandomWalk](-constant-distance-random-walk.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](index.md)>, environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](index.md), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)>, randomGenerator: RandomGenerator, distance: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), speed: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))

## Parameters

jvm

| | |
|---|---|
|  | <T> concentration type |
| environment | environment containing the node |
| node | the node to move |
| reaction | the reaction containing this action |
| randomGenerator | random number generator to use for the decisions |
| distance | the distance to travel before picking another one |
| speed | the speed |
