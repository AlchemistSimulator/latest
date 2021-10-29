---
title: it.unibo.alchemist.model.math
---
//[alchemist](../../index.html)/[it.unibo.alchemist.model.math](index.html)



# Package it.unibo.alchemist.model.math



## Types


| Name | Summary |
|---|---|
| [BidimensionalGaussian](-bidimensional-gaussian/index.html) | [jvm]<br>class [BidimensionalGaussian](-bidimensional-gaussian/index.html)(**amplitude**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **x0**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **y0**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **sigmaX**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **sigmaY**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) : BivariateFunction, [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)<br>A 2D gaussian function. |
| [LazyMutable](-lazy-mutable/index.html) | [jvm]<br>class [LazyMutable](-lazy-mutable/index.html)<[T](-lazy-mutable/index.html)>(**initializer**: () -> [T](-lazy-mutable/index.html)) : [ReadWriteProperty](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.properties/-read-write-property/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?, [T](-lazy-mutable/index.html)> <br>A delegate allowing to lazily initialise a non-null mutable variable (= var). |
| [RealDistributionUtil](-real-distribution-util/index.html) | [jvm]<br>class [RealDistributionUtil](-real-distribution-util/index.html)<br>Utility to translate statistics names into a RealDistribution. |


## Functions


| Name | Summary |
|---|---|
| [lazyMutable](lazy-mutable.html) | [jvm]<br>fun <[T](lazy-mutable.html)> [lazyMutable](lazy-mutable.html)(initializer: () -> [T](lazy-mutable.html)): [LazyMutable](-lazy-mutable/index.html)<[T](lazy-mutable.html)><br>Creates an instance of [LazyMutable](-lazy-mutable/index.html) with the given [initializer](lazy-mutable.html). |

