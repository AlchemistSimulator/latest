//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.timedistributions](../index.md)/[MoleculeControlledTimeDistribution](index.md)

# MoleculeControlledTimeDistribution

[jvm]\
class [MoleculeControlledTimeDistribution](index.md)<[T](index.md)>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()constructor(**incarnation**: [Incarnation](../../it.unibo.alchemist.model.interfaces/-incarnation/index.md)<[T](index.md), *>, **node**: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>, **molecule**: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md), **property**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, **start**: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md), **errorDistribution**: RealDistribution?) : [AnyRealDistribution](../-any-real-distribution/index.md)<[T](index.md)> 

A special TimeDistribution that schedules the reaction after [start](start.md), according to the value of a [molecule](molecule.md) which contains the delta time. If a [property](property.md) is specified, the value to be interpreted as time delta is read from the incarnation. Otherwise, the [node](node.md) is accessed directly for reading the value.

It's possible to associate an [errorDistribution](error-distribution.md) to this time distribution, whose samples will be used to shift the time samples.

There are some conditions to be satisfied:

<ul><li>[molecule](molecule.md) must be modified exclusively by the reaction being scheduled</li><li>[molecule](molecule.md) must exist in the node. If it does not and the environment returns null, it is assumed to be zero</li><li>[molecule](molecule.md) must have a positive or zero value associated.</li><li>[molecule](molecule.md)'s concentration must have a type which is understandable as a positive number ([Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html), [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md), or a parse-able [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)).</li><li>the [errorDistribution](error-distribution.md)'s samples plus the value of the [molecule](molecule.md) concentration (or property value) **must** always be greater than zero. It is thus recommended to use an [errorDistribution](error-distribution.md) whose support lower bound is zero or greater</li></ul>

## Constructors

| | |
|---|---|
| [MoleculeControlledTimeDistribution](-molecule-controlled-time-distribution.md) | [jvm]<br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()<br>fun <[T](index.md)> [MoleculeControlledTimeDistribution](-molecule-controlled-time-distribution.md)(incarnation: [Incarnation](../../it.unibo.alchemist.model.interfaces/-incarnation/index.md)<[T](index.md), *>, randomGenerator: RandomGenerator, node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>, molecule: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md), property: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, start: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md) = Time.ZERO, distributionName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), vararg distributionParametrs: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) |
| [MoleculeControlledTimeDistribution](-molecule-controlled-time-distribution.md) | [jvm]<br>fun <[T](index.md)> [MoleculeControlledTimeDistribution](-molecule-controlled-time-distribution.md)(incarnation: [Incarnation](../../it.unibo.alchemist.model.interfaces/-incarnation/index.md)<[T](index.md), *>, randomGenerator: RandomGenerator, node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>, molecule: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md), start: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md) = Time.ZERO, distributionName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), vararg distributionParametrs: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) |
| [MoleculeControlledTimeDistribution](-molecule-controlled-time-distribution.md) | [jvm]<br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()<br>fun <[T](index.md)> [MoleculeControlledTimeDistribution](-molecule-controlled-time-distribution.md)(incarnation: [Incarnation](../../it.unibo.alchemist.model.interfaces/-incarnation/index.md)<[T](index.md), *>, node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>, molecule: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md), property: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, start: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md) = Time.ZERO, errorDistribution: RealDistribution? = null) |

## Types

| Name | Summary |
|---|---|
| [Companion](-companion/index.md) | [jvm]<br>object [Companion](-companion/index.md) |

## Functions

| Name | Summary |
|---|---|
| [cloneOnNewNode](clone-on-new-node.md) | [jvm]<br>open override fun [cloneOnNewNode](clone-on-new-node.md)(destination: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>, currentTime: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md)?): [MoleculeControlledTimeDistribution](index.md)<[T](index.md)> |
| [getDistribution](index.md#-1512055053%2FFunctions%2F-267951372) | [jvm]<br>fun [getDistribution](index.md#-1512055053%2FFunctions%2F-267951372)(): RealDistribution |
| [getNextOccurence](../-abstract-distribution/get-next-occurence.md) | [jvm]<br>override fun [getNextOccurence](../-abstract-distribution/get-next-occurence.md)(): [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md) |
| [getRate](../-any-real-distribution/get-rate.md) | [jvm]<br>override fun [getRate](../-any-real-distribution/get-rate.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [setNextOccurrence](index.md#2016475877%2FFunctions%2F-267951372) | [jvm]<br>fun [setNextOccurrence](index.md#2016475877%2FFunctions%2F-267951372)(t: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md)) |
| [update](index.md#-1180668094%2FFunctions%2F-267951372) | [jvm]<br>override fun [update](index.md#-1180668094%2FFunctions%2F-267951372)(currentTime: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md), hasBeenExecuted: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), additionalParameter: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](index.md), *>) |

## Properties

| Name | Summary |
|---|---|
| [errorDistribution](error-distribution.md) | [jvm]<br>val [errorDistribution](error-distribution.md): RealDistribution? = null |
| [molecule](molecule.md) | [jvm]<br>val [molecule](molecule.md): [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md) |
| [node](node.md) | [jvm]<br>val [node](node.md): [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)> |
| [property](property.md) | [jvm]<br>val [property](property.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [start](start.md) | [jvm]<br>val [start](start.md): [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md) |
