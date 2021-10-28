//[alchemist](../../index.md)/[it.unibo.alchemist](index.md)/[intersectsBoundsExcluded](intersects-bounds-excluded.md)

# intersectsBoundsExcluded

[jvm]\
fun <[T](intersects-bounds-excluded.md) : [Comparable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-comparable/index.html)<[T](intersects-bounds-excluded.md)>> [ClosedRange](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.ranges/-closed-range/index.html)<[T](intersects-bounds-excluded.md)>.[intersectsBoundsExcluded](intersects-bounds-excluded.md)(other: [ClosedRange](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.ranges/-closed-range/index.html)<[T](intersects-bounds-excluded.md)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)

Checks whether two ranges intersect, excluding their bounds (i.e., excluding both [ClosedRange.start](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.ranges/-closed-range/start.html) and [ClosedRange.endInclusive](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.ranges/-closed-range/end-inclusive.html)). This means false is returned in case the ranges share a single endpoint.
