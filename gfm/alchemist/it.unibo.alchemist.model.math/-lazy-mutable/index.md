//[alchemist](../../../index.md)/[it.unibo.alchemist.model.math](../index.md)/[LazyMutable](index.md)

# LazyMutable

[jvm]\
class [LazyMutable](index.md)<[T](index.md)>(**initializer**: () -> [T](index.md)) : [ReadWriteProperty](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.properties/-read-write-property/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?, [T](index.md)> 

A delegate allowing to lazily initialise a non-null mutable variable (= var).

## Constructors

| | |
|---|---|
| [LazyMutable](-lazy-mutable.md) | [jvm]<br>fun <[T](index.md)> [LazyMutable](-lazy-mutable.md)(initializer: () -> [T](index.md)) |

## Functions

| Name | Summary |
|---|---|
| [getValue](get-value.md) | [jvm]<br>open operator override fun [getValue](get-value.md)(thisRef: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?, property: [KProperty](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-property/index.html)<*>): [T](index.md) |
| [setValue](set-value.md) | [jvm]<br>open operator override fun [setValue](set-value.md)(thisRef: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?, property: [KProperty](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-property/index.html)<*>, value: [T](index.md)) |
