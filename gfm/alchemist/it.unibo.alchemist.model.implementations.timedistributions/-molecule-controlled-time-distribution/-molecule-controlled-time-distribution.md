//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.timedistributions](../index.md)/[MoleculeControlledTimeDistribution](index.md)/[MoleculeControlledTimeDistribution](-molecule-controlled-time-distribution.md)

# MoleculeControlledTimeDistribution

[jvm]\

@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()

fun <[T](index.md)> [MoleculeControlledTimeDistribution](-molecule-controlled-time-distribution.md)(incarnation: [Incarnation](../../it.unibo.alchemist.model.interfaces/-incarnation/index.md)<[T](index.md), *>, randomGenerator: RandomGenerator, node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>, molecule: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md), property: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, start: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md) = Time.ZERO, distributionName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), vararg distributionParametrs: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))

fun <[T](index.md)> [MoleculeControlledTimeDistribution](-molecule-controlled-time-distribution.md)(incarnation: [Incarnation](../../it.unibo.alchemist.model.interfaces/-incarnation/index.md)<[T](index.md), *>, randomGenerator: RandomGenerator, node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>, molecule: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md), start: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md) = Time.ZERO, distributionName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), vararg distributionParametrs: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))

@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()

fun <[T](index.md)> [MoleculeControlledTimeDistribution](-molecule-controlled-time-distribution.md)(incarnation: [Incarnation](../../it.unibo.alchemist.model.interfaces/-incarnation/index.md)<[T](index.md), *>, node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>, molecule: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md), property: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, start: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md) = Time.ZERO, errorDistribution: RealDistribution? = null)
