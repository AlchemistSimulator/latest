//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces.geometry.euclidean2d](../index.md)/[Segment2D](index.md)/[toRange](to-range.md)

# toRange

[jvm]\
open fun [toRange](to-range.md)(getXCoords: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = this.isHorizontal): [ClosedRange](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.ranges/-closed-range/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)>

Maps the segment a [ClosedRange](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.ranges/-closed-range/index.html), this is done by extracting either the X coordinates or the Y coordinates of the two endpoints of the segment. [getXCoords](to-range.md) indicates which pair of coordinates should be extracted (defaults to [isHorizontal](is-horizontal.md)). This can be useful e.g. to represent portions of axis-aligned segments without creating new ones.
