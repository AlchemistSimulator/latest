---
title: toRange
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces.geometry.euclidean2d](../index.html)/[Segment2D](index.html)/[toRange](to-range.html)



# toRange



[jvm]\
open fun [toRange](to-range.html)(getXCoords: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = this.isHorizontal): [ClosedRange](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.ranges/-closed-range/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)>



Maps the segment a [ClosedRange](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.ranges/-closed-range/index.html), this is done by extracting either the X coordinates or the Y coordinates of the two endpoints of the segment. [getXCoords](to-range.html) indicates which pair of coordinates should be extracted (defaults to [isHorizontal](is-horizontal.html)). This can be useful e.g. to represent portions of axis-aligned segments without creating new ones.




