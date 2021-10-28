---
title: minus
---
//[alchemist](../../index.html)/[it.unibo.alchemist](index.html)/[minus](minus.html)



# minus



[jvm]\
infix operator fun <[T](minus.html) : [Comparable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-comparable/index.html)<[T](minus.html)>> [ClosedRange](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.ranges/-closed-range/index.html)<[T](minus.html)>.[minus](minus.html)(other: [ClosedRange](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.ranges/-closed-range/index.html)<[T](minus.html)>): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[ClosedRange](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.ranges/-closed-range/index.html)<[T](minus.html)>>



Performs a subtraction between ranges. The operation can produce an empty list (e.g. if the current range is contained in the [other](minus.html) one), a list featuring a single element, or a list featuring two elements (e.g. if the current range contains the [other](minus.html) one).




