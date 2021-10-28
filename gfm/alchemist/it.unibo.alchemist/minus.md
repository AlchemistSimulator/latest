//[alchemist](../../index.md)/[it.unibo.alchemist](index.md)/[minus](minus.md)

# minus

[jvm]\
infix operator fun <[T](minus.md) : [Comparable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-comparable/index.html)<[T](minus.md)>> [ClosedRange](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.ranges/-closed-range/index.html)<[T](minus.md)>.[minus](minus.md)(other: [ClosedRange](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.ranges/-closed-range/index.html)<[T](minus.md)>): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[ClosedRange](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.ranges/-closed-range/index.html)<[T](minus.md)>>

Performs a subtraction between ranges. The operation can produce an empty list (e.g. if the current range is contained in the [other](minus.md) one), a list featuring a single element, or a list featuring two elements (e.g. if the current range contains the [other](minus.md) one).
