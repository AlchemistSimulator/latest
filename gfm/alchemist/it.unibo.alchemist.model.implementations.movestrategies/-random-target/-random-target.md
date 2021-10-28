//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.movestrategies](../index.md)/[RandomTarget](index.md)/[RandomTarget](-random-target.md)

# RandomTarget

[jvm]\
fun <[T](index.md)> [RandomTarget](-random-target.md)(env: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](index.md), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)>, node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>, directionRng: RandomGenerator, distanceDistribution: RealDistribution)

Handy constructor for Alchemist where the object to move is a node in the env.

[jvm]\
fun <[T](index.md)> [RandomTarget](-random-target.md)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](index.md), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)>, getCurrentPosition: () -> [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md), makePosition: ([Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) -> [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md), directionRng: RandomGenerator, distanceDistribution: RealDistribution)
