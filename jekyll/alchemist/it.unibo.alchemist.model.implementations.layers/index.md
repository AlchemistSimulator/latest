---
title: it.unibo.alchemist.model.implementations.layers
---
//[alchemist](../../index.html)/[it.unibo.alchemist.model.implementations.layers](index.html)



# Package it.unibo.alchemist.model.implementations.layers



## Types


| Name | Summary |
|---|---|
| [BidimensionalGaussianLayer](-bidimensional-gaussian-layer/index.html) | [jvm]<br>open class [BidimensionalGaussianLayer](-bidimensional-gaussian-layer/index.html)<[P](-bidimensional-gaussian-layer/index.html) : [Position2D](../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<[P](-bidimensional-gaussian-layer/index.html)>>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()constructor(**baseline**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **centerX**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **centerY**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **norm**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **sigmaX**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **sigmaY**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) : [Layer](../it.unibo.alchemist.model.interfaces/-layer/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), [P](-bidimensional-gaussian-layer/index.html)> <br>A [Layer](../it.unibo.alchemist.model.interfaces/-layer/index.html) based on a [2D gaussian function](../it.unibo.alchemist.model.math/-bidimensional-gaussian/index.html) and an optional baseline value. |
| [BiomolGradientLayer](-biomol-gradient-layer/index.html) | [jvm]<br>class [BiomolGradientLayer](-biomol-gradient-layer/index.html)<[P](-biomol-gradient-layer/index.html) : [Position2D](../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<[P](../it.unibo.alchemist.model/-biochemistry-incarnation/index.html)>?> : [Layer](../it.unibo.alchemist.model.interfaces/-layer/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html), [P](../it.unibo.alchemist.model/-biochemistry-incarnation/index.html)> <br>A [Layer](../it.unibo.alchemist.model.interfaces/-layer/index.html) representing a linear distribution in space of a molecule. |
| [StepLayer](-step-layer/index.html) | [jvm]<br>class [StepLayer](-step-layer/index.html)<[T](-step-layer/index.html), [P](-step-layer/index.html) : [Position2D](../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<out [P](-uniform-layer/index.html)>?> : [Layer](../it.unibo.alchemist.model.interfaces/-layer/index.html)<[T](-uniform-layer/index.html), [P](-uniform-layer/index.html)> <br>Implements a [Layer](../it.unibo.alchemist.model.interfaces/-layer/index.html) with a discontinue spatial distribution: the plane is divided in two parts, both with a constant concentration but with a different in value. |
| [UniformLayer](-uniform-layer/index.html) | [jvm]<br>class [UniformLayer](-uniform-layer/index.html)<[T](-uniform-layer/index.html), [P](-uniform-layer/index.html) : [Position](../it.unibo.alchemist.model.interfaces/-position/index.html)<out [P](-uniform-layer/index.html)>?> : [Layer](../it.unibo.alchemist.model.interfaces/-layer/index.html)<[T](-uniform-layer/index.html), [P](-uniform-layer/index.html)> <br>a Layer where the concentration is the same at every point in space. |

