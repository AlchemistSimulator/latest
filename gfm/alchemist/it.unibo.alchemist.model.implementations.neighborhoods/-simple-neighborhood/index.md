//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.neighborhoods](../index.md)/[SimpleNeighborhood](index.md)

# SimpleNeighborhood

[jvm]\
class [SimpleNeighborhood](index.md)<[T](index.md), [P](index.md) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<[P](index.md)>> : [Neighborhood](../../it.unibo.alchemist.model.interfaces/-neighborhood/index.md)<[T](index.md)> 

A basic implementation of the [Neighborhood](../../it.unibo.alchemist.model.interfaces/-neighborhood/index.md) interface.

## Functions

| Name | Summary |
|---|---|
| [add](add.md) | [jvm]<br>open override fun [add](add.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>): [SimpleNeighborhood](index.md)<[T](index.md), [P](index.md)> |
| [contains](contains.md) | [jvm]<br>open operator override fun [contains](contains.md)(n: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [equals](equals.md) | [jvm]<br>open operator override fun [equals](equals.md)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [forEach](index.md#1379299152%2FFunctions%2F-267951372) | [jvm]<br>open fun [forEach](index.md#1379299152%2FFunctions%2F-267951372)(p0: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<in [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>>) |
| [getCenter](get-center.md) | [jvm]<br>open override fun [getCenter](get-center.md)(): [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)> |
| [getNeighborByNumber](get-neighbor-by-number.md) | [jvm]<br>open override fun [getNeighborByNumber](get-neighbor-by-number.md)(num: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)> |
| [getNeighbors](get-neighbors.md) | [jvm]<br>open override fun [getNeighbors](get-neighbors.md)(): ListSet<out [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>> |
| [hashCode](hash-code.md) | [jvm]<br>open override fun [hashCode](hash-code.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [isEmpty](is-empty.md) | [jvm]<br>open override fun [isEmpty](is-empty.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [iterator](iterator.md) | [jvm]<br>open operator override fun [iterator](iterator.md)(): [MutableIterator](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-iterator/index.html)<[Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>> |
| [remove](remove.md) | [jvm]<br>open override fun [remove](remove.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>): [SimpleNeighborhood](index.md)<[T](index.md), [P](index.md)> |
| [size](size.md) | [jvm]<br>open override fun [size](size.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [spliterator](../../it.unibo.alchemist.loader.deployments/-close-to-g-p-s-trace/index.md#-1387152138%2FFunctions%2F-267951372) | [jvm]<br>open fun [spliterator](../../it.unibo.alchemist.loader.deployments/-close-to-g-p-s-trace/index.md#-1387152138%2FFunctions%2F-267951372)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>> |
| [toString](to-string.md) | [jvm]<br>open override fun [toString](to-string.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
