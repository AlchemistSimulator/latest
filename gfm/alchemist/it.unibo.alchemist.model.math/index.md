//[alchemist](../../index.md)/[it.unibo.alchemist.model.math](index.md)

# Package it.unibo.alchemist.model.math

## Types

| Name | Summary |
|---|---|
| [BidimensionalGaussian](-bidimensional-gaussian/index.md) | [jvm]<br>class [BidimensionalGaussian](-bidimensional-gaussian/index.md)(**amplitude**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **x0**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **y0**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **sigmaX**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **sigmaY**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) : BivariateFunction, [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)<br>A 2D gaussian function. |
| [LazyMutable](-lazy-mutable/index.md) | [jvm]<br>class [LazyMutable](-lazy-mutable/index.md)<[T](-lazy-mutable/index.md)>(**initializer**: () -> [T](-lazy-mutable/index.md)) : [ReadWriteProperty](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.properties/-read-write-property/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?, [T](-lazy-mutable/index.md)> <br>A delegate allowing to lazily initialise a non-null mutable variable (= var). |
| [RealDistributionUtil](-real-distribution-util/index.md) | [jvm]<br>class [RealDistributionUtil](-real-distribution-util/index.md)<br>Utility to translate statistics names into a RealDistribution. |

## Functions

| Name | Summary |
|---|---|
| [lazyMutable](lazy-mutable.md) | [jvm]<br>fun <[T](lazy-mutable.md)> [lazyMutable](lazy-mutable.md)(initializer: () -> [T](lazy-mutable.md)): [LazyMutable](-lazy-mutable/index.md)<[T](lazy-mutable.md)><br>Creates an instance of [LazyMutable](-lazy-mutable/index.md) with the given [initializer](lazy-mutable.md). |
