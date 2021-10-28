//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.environments](../index.md)/[AbstractEnvironment](index.md)/[getSizeInDistanceUnits](get-size-in-distance-units.md)

# getSizeInDistanceUnits

[jvm]\
open fun [getSizeInDistanceUnits](get-size-in-distance-units.md)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)>

Override this method if units measuring distance do not match with units used for coordinates. For instance, if your space is non-Euclidean, or if you are using polar coordinates. A notable example is using geographical latitude-longitude as y-x coordinates and meters as distance measure.
