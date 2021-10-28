//[alchemist](../../../index.md)/[it.unibo.alchemist.model.math](../index.md)/[BidimensionalGaussian](index.md)

# BidimensionalGaussian

[jvm]\
class [BidimensionalGaussian](index.md)(**amplitude**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **x0**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **y0**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **sigmaX**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **sigmaY**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) : BivariateFunction, [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)

A 2D gaussian function.

## Constructors

| | |
|---|---|
| [BidimensionalGaussian](-bidimensional-gaussian.md) | [jvm]<br>fun [BidimensionalGaussian](-bidimensional-gaussian.md)(amplitude: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), x0: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), y0: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), sigmaX: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), sigmaY: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) |

## Types

| Name | Summary |
|---|---|
| [Companion](-companion/index.md) | [jvm]<br>object [Companion](-companion/index.md) |

## Functions

| Name | Summary |
|---|---|
| [integral](integral.md) | [jvm]<br>fun [integral](integral.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>The integral of the function. |
| [value](value.md) | [jvm]<br>open override fun [value](value.md)(x: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), y: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
