---
title: LazyMutable
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.math](../index.html)/[LazyMutable](index.html)



# LazyMutable



[jvm]\
class [LazyMutable](index.html)<[T](index.html)>(**initializer**: () -> [T](index.html)) : [ReadWriteProperty](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.properties/-read-write-property/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?, [T](index.html)> 

A delegate allowing to lazily initialise a non-null mutable variable (= var).



## Constructors


| | |
|---|---|
| [LazyMutable](-lazy-mutable.html) | [jvm]<br>fun <[T](index.html)> [LazyMutable](-lazy-mutable.html)(initializer: () -> [T](index.html)) |


## Functions


| Name | Summary |
|---|---|
| [getValue](get-value.html) | [jvm]<br>open operator override fun [getValue](get-value.html)(thisRef: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?, property: [KProperty](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-property/index.html)<*>): [T](index.html) |
| [setValue](set-value.html) | [jvm]<br>open operator override fun [setValue](set-value.html)(thisRef: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?, property: [KProperty](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-property/index.html)<*>, value: [T](index.html)) |

