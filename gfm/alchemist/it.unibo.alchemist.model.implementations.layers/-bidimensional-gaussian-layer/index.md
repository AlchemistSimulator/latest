//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.layers](../index.md)/[BidimensionalGaussianLayer](index.md)

# BidimensionalGaussianLayer

[jvm]\
open class [BidimensionalGaussianLayer](index.md)<[P](index.md) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.md)<[P](index.md)>>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()constructor(**baseline**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **centerX**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **centerY**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **norm**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **sigmaX**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **sigmaY**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) : [Layer](../../it.unibo.alchemist.model.interfaces/-layer/index.md)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), [P](index.md)> 

A [Layer](../../it.unibo.alchemist.model.interfaces/-layer/index.md) based on a [2D gaussian function](../../it.unibo.alchemist.model.math/-bidimensional-gaussian/index.md) and an optional baseline value.

## Parameters

jvm

| | |
|---|---|
| centerX | x coord of the layer's center. |
| centerY | y coord of the layer's center. |

## Constructors

| | |
|---|---|
| [BidimensionalGaussianLayer](-bidimensional-gaussian-layer.md) | [jvm]<br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()<br>fun [BidimensionalGaussianLayer](-bidimensional-gaussian-layer.md)(baseline: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 0.0, centerX: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), centerY: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), norm: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), sigmaX: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), sigmaY: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = sigmaX)<br>x coord of the layer's center. |

## Functions

| Name | Summary |
|---|---|
| [getValue](get-value.md) | [jvm]<br>open override fun [getValue](get-value.md)(p: [P](index.md)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |

## Properties

| Name | Summary |
|---|---|
| [centerX](center-x.md) | [jvm]<br>val [centerX](center-x.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>x coord of the layer's center. |
| [centerY](center-y.md) | [jvm]<br>val [centerY](center-y.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>y coord of the layer's center. |
| [function](function.md) | [jvm]<br>val [function](function.md): [BidimensionalGaussian](../../it.unibo.alchemist.model.math/-bidimensional-gaussian/index.md)<br>The function on which the layer is based. |
