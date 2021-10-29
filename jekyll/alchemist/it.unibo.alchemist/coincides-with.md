---
title: coincidesWith
---
//[alchemist](../../index.html)/[it.unibo.alchemist](index.html)/[coincidesWith](coincides-with.html)



# coincidesWith



[jvm]\
fun <[T](coincides-with.html) : [Comparable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-comparable/index.html)<[T](coincides-with.html)>> [ClosedRange](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.ranges/-closed-range/index.html)<[T](coincides-with.html)>.[coincidesWith](coincides-with.html)(other: [ClosedRange](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.ranges/-closed-range/index.html)<[T](coincides-with.html)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)



Checks whether two ranges coincide. It's a different way of checking if they're equals, which doesn't depend on their actual implementation. Note that the way you obtain a range may influence the actual class used, and you can have two coincident ranges which don't result equals because of different classes.




