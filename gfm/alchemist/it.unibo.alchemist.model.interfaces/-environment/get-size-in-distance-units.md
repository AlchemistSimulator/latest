//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces](../index.md)/[Environment](index.md)/[getSizeInDistanceUnits](get-size-in-distance-units.md)

# getSizeInDistanceUnits

[jvm]\
abstract fun [getSizeInDistanceUnits](get-size-in-distance-units.md)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)>

This method returns the size of the environment as an array of length [getDimensions](get-dimensions.md). This method must return distance measured with the same unit used for measuring distances. It may or may not return the same result of [getSize](get-size.md)

#### Return

the size of this environment
