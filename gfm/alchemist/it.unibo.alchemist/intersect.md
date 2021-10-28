//[alchemist](../../index.md)/[it.unibo.alchemist](index.md)/[intersect](intersect.md)

# intersect

[jvm]\
fun <[T](intersect.md) : [Comparable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-comparable/index.html)<[T](intersect.md)>> [ClosedRange](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.ranges/-closed-range/index.html)<[T](intersect.md)>.[intersect](intersect.md)(other: [ClosedRange](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.ranges/-closed-range/index.html)<[T](intersect.md)>): [ClosedRange](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.ranges/-closed-range/index.html)<[T](intersect.md)>?

Finds the intersection between two ranges, the resulting range may feature a single value (if the ranges only share an endpoint) or can be null, if they don't intersect at all.
