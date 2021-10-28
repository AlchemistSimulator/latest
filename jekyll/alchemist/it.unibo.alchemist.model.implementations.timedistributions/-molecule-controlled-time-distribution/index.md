---
title: MoleculeControlledTimeDistribution
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.timedistributions](../index.html)/[MoleculeControlledTimeDistribution](index.html)



# MoleculeControlledTimeDistribution



[jvm]\
class [MoleculeControlledTimeDistribution](index.html)<[T](index.html)>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()constructor(**incarnation**: [Incarnation](../../it.unibo.alchemist.model.interfaces/-incarnation/index.html)<[T](index.html), *>, **node**: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](index.html)>, **molecule**: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html), **property**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, **start**: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html), **errorDistribution**: RealDistribution?) : [AnyRealDistribution](../-any-real-distribution/index.html)<[T](index.html)> 

A special TimeDistribution that schedules the reaction after [start](start.html), according to the value of a [molecule](molecule.html) which contains the delta time. If a [property](property.html) is specified, the value to be interpreted as time delta is read from the incarnation. Otherwise, the [node](node.html) is accessed directly for reading the value.



It's possible to associate an [errorDistribution](error-distribution.html) to this time distribution, whose samples will be used to shift the time samples.



There are some conditions to be satisfied:



<ul><li>[molecule](molecule.html) must be modified exclusively by the reaction being scheduled</li><li>[molecule](molecule.html) must exist in the node. If it does not and the environment returns null, it is assumed to be zero</li><li>[molecule](molecule.html) must have a positive or zero value associated.</li><li>[molecule](molecule.html)'s concentration must have a type which is understandable as a positive number ([Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html), [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html), or a parse-able [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)).</li><li>the [errorDistribution](error-distribution.html)'s samples plus the value of the [molecule](molecule.html) concentration (or property value) **must** always be greater than zero. It is thus recommended to use an [errorDistribution](error-distribution.html) whose support lower bound is zero or greater</li></ul>



## Constructors


| | |
|---|---|
| [MoleculeControlledTimeDistribution](-molecule-controlled-time-distribution.html) | [jvm]<br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()<br>fun <[T](index.html)> [MoleculeControlledTimeDistribution](-molecule-controlled-time-distribution.html)(incarnation: [Incarnation](../../it.unibo.alchemist.model.interfaces/-incarnation/index.html)<[T](index.html), *>, randomGenerator: RandomGenerator, node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](index.html)>, molecule: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html), property: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, start: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html) = Time.ZERO, distributionName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), vararg distributionParametrs: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) |
| [MoleculeControlledTimeDistribution](-molecule-controlled-time-distribution.html) | [jvm]<br>fun <[T](index.html)> [MoleculeControlledTimeDistribution](-molecule-controlled-time-distribution.html)(incarnation: [Incarnation](../../it.unibo.alchemist.model.interfaces/-incarnation/index.html)<[T](index.html), *>, randomGenerator: RandomGenerator, node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](index.html)>, molecule: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html), start: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html) = Time.ZERO, distributionName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), vararg distributionParametrs: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) |
| [MoleculeControlledTimeDistribution](-molecule-controlled-time-distribution.html) | [jvm]<br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()<br>fun <[T](index.html)> [MoleculeControlledTimeDistribution](-molecule-controlled-time-distribution.html)(incarnation: [Incarnation](../../it.unibo.alchemist.model.interfaces/-incarnation/index.html)<[T](index.html), *>, node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](index.html)>, molecule: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html), property: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, start: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html) = Time.ZERO, errorDistribution: RealDistribution? = null) |


## Types


| Name | Summary |
|---|---|
| [Companion](-companion/index.html) | [jvm]<br>object [Companion](-companion/index.html) |


## Functions


| Name | Summary |
|---|---|
| [cloneOnNewNode](clone-on-new-node.html) | [jvm]<br>open override fun [cloneOnNewNode](clone-on-new-node.html)(destination: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](index.html)>, currentTime: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html)?): [MoleculeControlledTimeDistribution](index.html)<[T](index.html)> |
| [getDistribution](index.html#-1512055053%2FFunctions%2F-134779887) | [jvm]<br>fun [getDistribution](index.html#-1512055053%2FFunctions%2F-134779887)(): RealDistribution |
| [getNextOccurence](../-abstract-distribution/get-next-occurence.html) | [jvm]<br>override fun [getNextOccurence](../-abstract-distribution/get-next-occurence.html)(): [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html) |
| [getRate](../-any-real-distribution/get-rate.html) | [jvm]<br>override fun [getRate](../-any-real-distribution/get-rate.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [setNextOccurrence](index.html#2016475877%2FFunctions%2F-134779887) | [jvm]<br>fun [setNextOccurrence](index.html#2016475877%2FFunctions%2F-134779887)(t: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html)) |
| [update](index.html#-1180668094%2FFunctions%2F-134779887) | [jvm]<br>override fun [update](index.html#-1180668094%2FFunctions%2F-134779887)(currentTime: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html), hasBeenExecuted: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), additionalParameter: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](index.html), *>) |


## Properties


| Name | Summary |
|---|---|
| [errorDistribution](error-distribution.html) | [jvm]<br>val [errorDistribution](error-distribution.html): RealDistribution? = null |
| [molecule](molecule.html) | [jvm]<br>val [molecule](molecule.html): [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html) |
| [node](node.html) | [jvm]<br>val [node](node.html): [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](index.html)> |
| [property](property.html) | [jvm]<br>val [property](property.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [start](start.html) | [jvm]<br>val [start](start.html): [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html) |

