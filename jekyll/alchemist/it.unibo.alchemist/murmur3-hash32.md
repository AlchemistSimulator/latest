---
title: murmur3Hash32
---
//[alchemist](../../index.html)/[it.unibo.alchemist](index.html)/[murmur3Hash32](murmur3-hash32.html)



# murmur3Hash32



[jvm]\
fun <[T](murmur3-hash32.html)> [murmur3Hash32](murmur3-hash32.html)(vararg data: [T](murmur3-hash32.html)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)



Hashes a number of [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)s with Hashing.murmur3_32. The charset used for strings is [Charsets.UTF_16](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.text/-charsets/-u-t-f_16.html). For [Iterable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html) and [Sequence](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.sequences/-sequence/index.html), the elements are hashed rather than the [Iterable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html) or [Sequence](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.sequences/-sequence/index.html) itself. If the [Iterable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html) or [Sequence](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.sequences/-sequence/index.html) contains a null element, it is skipped.



## Parameters


jvm

| | |
|---|---|
| data | the data to hash |




