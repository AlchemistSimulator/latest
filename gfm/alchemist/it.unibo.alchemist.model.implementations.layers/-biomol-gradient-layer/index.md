//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.layers](../index.md)/[BiomolGradientLayer](index.md)

# BiomolGradientLayer

[jvm]\
class [BiomolGradientLayer](index.md)<[P](index.md) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.md)<[P](../../it.unibo.alchemist.model.implementations.environments/-abstract2-d-environment/index.md)>?> : [Layer](../../it.unibo.alchemist.model.interfaces/-layer/index.md)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html), [P](../../it.unibo.alchemist.model.implementations.environments/-abstract2-d-environment/index.md)> 

A [Layer](../../it.unibo.alchemist.model.interfaces/-layer/index.md) representing a linear distribution in space of a molecule.

## Parameters

jvm

| | |
|---|---|
| <P> | [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.md) type |

## Constructors

| | |
|---|---|
| [BiomolGradientLayer](-biomol-gradient-layer.md) | [jvm]<br>open fun [BiomolGradientLayer](-biomol-gradient-layer.md)(directionX: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), directionY: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), unitVariation: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), offset: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Initialize a gradient layer which grows in concentration proportionally in space. |
| [BiomolGradientLayer](-biomol-gradient-layer.md) | [jvm]<br>open fun [BiomolGradientLayer](-biomol-gradient-layer.md)(direction: [P](../../it.unibo.alchemist.model.implementations.environments/-abstract2-d-environment/index.md), unitVariation: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), offset: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Initialize a gradient layer which grows in concentration proportionally in space. |

## Functions

| Name | Summary |
|---|---|
| [getParameters](get-parameters.md) | [jvm]<br>open fun [getParameters](get-parameters.md)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)><br>the parameters describing this spatial distribution, that's actually a plain. |
| [getValue](get-value.md) | [jvm]<br>open fun [getValue](get-value.md)(p: [P](../../it.unibo.alchemist.model.implementations.environments/-abstract2-d-environment/index.md)): [Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html) |
| [toString](to-string.md) | [jvm]<br>open fun [toString](to-string.md)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |

## Properties

| Name | Summary |
|---|---|
| [steep](steep.md) | [jvm]<br>private val [steep](steep.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
