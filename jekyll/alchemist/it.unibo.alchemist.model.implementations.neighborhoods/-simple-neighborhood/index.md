---
title: SimpleNeighborhood
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.neighborhoods](../index.html)/[SimpleNeighborhood](index.html)



# SimpleNeighborhood



[jvm]\
class [SimpleNeighborhood](index.html)<[T](index.html), [P](index.html) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<[P](index.html)>> : [Neighborhood](../../it.unibo.alchemist.model.interfaces/-neighborhood/index.html)<[T](index.html)> 

A basic implementation of the [Neighborhood](../../it.unibo.alchemist.model.interfaces/-neighborhood/index.html) interface.



## Functions


| Name | Summary |
|---|---|
| [add](add.html) | [jvm]<br>open override fun [add](add.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](index.html)>): [SimpleNeighborhood](index.html)<[T](index.html), [P](index.html)> |
| [contains](contains.html) | [jvm]<br>open operator override fun [contains](contains.html)(n: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](index.html)>?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [equals](equals.html) | [jvm]<br>open operator override fun [equals](equals.html)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [forEach](index.html#1379299152%2FFunctions%2F-134779887) | [jvm]<br>open fun [forEach](index.html#1379299152%2FFunctions%2F-134779887)(p0: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<in [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](index.html)>>) |
| [getCenter](get-center.html) | [jvm]<br>open override fun [getCenter](get-center.html)(): [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](index.html)> |
| [getNeighborByNumber](get-neighbor-by-number.html) | [jvm]<br>open override fun [getNeighborByNumber](get-neighbor-by-number.html)(num: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](index.html)> |
| [getNeighbors](get-neighbors.html) | [jvm]<br>open override fun [getNeighbors](get-neighbors.html)(): ListSet<out [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](index.html)>> |
| [hashCode](hash-code.html) | [jvm]<br>open override fun [hashCode](hash-code.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [isEmpty](is-empty.html) | [jvm]<br>open override fun [isEmpty](is-empty.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [iterator](iterator.html) | [jvm]<br>open operator override fun [iterator](iterator.html)(): [MutableIterator](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-iterator/index.html)<[Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](index.html)>> |
| [remove](remove.html) | [jvm]<br>open override fun [remove](remove.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](index.html)>): [SimpleNeighborhood](index.html)<[T](index.html), [P](index.html)> |
| [size](size.html) | [jvm]<br>open override fun [size](size.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [spliterator](../../it.unibo.alchemist.loader.deployments/-close-to-g-p-s-trace/index.html#-1387152138%2FFunctions%2F-134779887) | [jvm]<br>open fun [spliterator](../../it.unibo.alchemist.loader.deployments/-close-to-g-p-s-trace/index.html#-1387152138%2FFunctions%2F-134779887)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](index.html)>> |
| [toString](to-string.html) | [jvm]<br>open override fun [toString](to-string.html)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

