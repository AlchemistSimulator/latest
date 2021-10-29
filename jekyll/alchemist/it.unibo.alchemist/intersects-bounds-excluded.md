---
title: intersectsBoundsExcluded
---
//[alchemist](../../index.html)/[it.unibo.alchemist](index.html)/[intersectsBoundsExcluded](intersects-bounds-excluded.html)



# intersectsBoundsExcluded



[jvm]\
fun <[T](intersects-bounds-excluded.html) : [Comparable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-comparable/index.html)<[T](intersects-bounds-excluded.html)>> [ClosedRange](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.ranges/-closed-range/index.html)<[T](intersects-bounds-excluded.html)>.[intersectsBoundsExcluded](intersects-bounds-excluded.html)(other: [ClosedRange](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.ranges/-closed-range/index.html)<[T](intersects-bounds-excluded.html)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)



Checks whether two ranges intersect, excluding their bounds (i.e., excluding both [ClosedRange.start](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.ranges/-closed-range/start.html) and [ClosedRange.endInclusive](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.ranges/-closed-range/end-inclusive.html)). This means false is returned in case the ranges share a single endpoint.




