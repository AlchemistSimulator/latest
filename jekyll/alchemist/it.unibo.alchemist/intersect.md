---
title: intersect
---
//[alchemist](../../index.html)/[it.unibo.alchemist](index.html)/[intersect](intersect.html)



# intersect



[jvm]\
fun <[T](intersect.html) : [Comparable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-comparable/index.html)<[T](intersect.html)>> [ClosedRange](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.ranges/-closed-range/index.html)<[T](intersect.html)>.[intersect](intersect.html)(other: [ClosedRange](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.ranges/-closed-range/index.html)<[T](intersect.html)>): [ClosedRange](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.ranges/-closed-range/index.html)<[T](intersect.html)>?



Finds the intersection between two ranges, the resulting range may feature a single value (if the ranges only share an endpoint) or can be null, if they don't intersect at all.




