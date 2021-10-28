//[alchemist](../../index.md)/[it.unibo.alchemist](index.md)/[coincidesWith](coincides-with.md)

# coincidesWith

[jvm]\
fun <[T](coincides-with.md) : [Comparable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-comparable/index.html)<[T](coincides-with.md)>> [ClosedRange](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.ranges/-closed-range/index.html)<[T](coincides-with.md)>.[coincidesWith](coincides-with.md)(other: [ClosedRange](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.ranges/-closed-range/index.html)<[T](coincides-with.md)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)

Checks whether two ranges coincide. It's a different way of checking if they're equals, which doesn't depend on their actual implementation. Note that the way you obtain a range may influence the actual class used, and you can have two coincident ranges which don't result equals because of different classes.
