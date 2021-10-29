---
title: BidimensionalGaussianLayer
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.layers](../index.html)/[BidimensionalGaussianLayer](index.html)



# BidimensionalGaussianLayer



[jvm]\
open class [BidimensionalGaussianLayer](index.html)<[P](index.html) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<[P](index.html)>>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()constructor(**baseline**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **centerX**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **centerY**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **norm**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **sigmaX**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **sigmaY**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) : [Layer](../../it.unibo.alchemist.model.interfaces/-layer/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), [P](index.html)> 

A [Layer](../../it.unibo.alchemist.model.interfaces/-layer/index.html) based on a [2D gaussian function](../../it.unibo.alchemist.model.math/-bidimensional-gaussian/index.html) and an optional baseline value.



## Parameters


jvm

| | |
|---|---|
| centerX | x coord of the layer's center. |
| centerY | y coord of the layer's center. |



## Constructors


| | |
|---|---|
| [BidimensionalGaussianLayer](-bidimensional-gaussian-layer.html) | [jvm]<br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()<br>fun [BidimensionalGaussianLayer](-bidimensional-gaussian-layer.html)(baseline: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 0.0, centerX: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), centerY: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), norm: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), sigmaX: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), sigmaY: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = sigmaX)<br>x coord of the layer's center. |


## Functions


| Name | Summary |
|---|---|
| [getValue](get-value.html) | [jvm]<br>open override fun [getValue](get-value.html)(p: [P](index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |


## Properties


| Name | Summary |
|---|---|
| [centerX](center-x.html) | [jvm]<br>val [centerX](center-x.html): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>x coord of the layer's center. |
| [centerY](center-y.html) | [jvm]<br>val [centerY](center-y.html): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>y coord of the layer's center. |
| [function](function.html) | [jvm]<br>val [function](function.html): [BidimensionalGaussian](../../it.unibo.alchemist.model.math/-bidimensional-gaussian/index.html)<br>The function on which the layer is based. |

