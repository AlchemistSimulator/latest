//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces](../index.md)/[Neighborhood](index.md)

# Neighborhood

[jvm]\
interface [Neighborhood](index.md)<[T](index.md)> : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html), [Cloneable](https://docs.oracle.com/javase/8/docs/api/java/lang/Cloneable.html), [Iterable](https://docs.oracle.com/javase/8/docs/api/java/lang/Iterable.html)<[Node](../-node/index.md)<[T](../-action/index.md)>> 

The type which describes the concentration of a molecule Interface for a neighborhood. When implementing it in a real class, please remember to correctly implement also the equals method inherited from Object.

## Parameters

jvm

| | |
|---|---|
| <T> | concentration type |

## Functions

| Name | Summary |
|---|---|
| [add](add.md) | [jvm]<br>abstract fun [add](add.md)(node: [Node](../-node/index.md)<[T](../-action/index.md)>): [Neighborhood](index.md)<[T](../-action/index.md)><br>the [Node](../-node/index.md) to add |
| [contains](contains.md) | [jvm]<br>abstract fun [contains](contains.md)(n: [Node](../-node/index.md)<[T](../-action/index.md)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Verifies if a node is contained inside a neighborhood. |
| [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-655675525%2FFunctions%2F-267951372) | [jvm]<br>open fun [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-655675525%2FFunctions%2F-267951372)(action: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |
| [getCenter](get-center.md) | [jvm]<br>abstract fun [getCenter](get-center.md)(): [Node](../-node/index.md)<[T](../-action/index.md)><br>Allows to access the central node. |
| [getNeighborByNumber](get-neighbor-by-number.md) | [jvm]<br>@[Deprecated](https://docs.oracle.com/javase/8/docs/api/java/lang/Deprecated.html)()<br>~~abstract~~ ~~fun~~ [~~getNeighborByNumber~~](get-neighbor-by-number.md)~~(~~~~num~~~~:~~ [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)~~)~~~~:~~ [Node](../-node/index.md)<[T](../-action/index.md)><br>Returns the num-th neighbor. |
| [getNeighbors](get-neighbors.md) | [jvm]<br>abstract fun [getNeighbors](get-neighbors.md)(): ListSet<out [Node](../-node/index.md)<[T](../-action/index.md)>><br>Allows to directly access every node in the neighborhood. |
| [isEmpty](is-empty.md) | [jvm]<br>abstract fun [isEmpty](is-empty.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>true if this neighborhood has no neighbors |
| [iterator](../../it.unibo.alchemist.loader.variables/-arbitrary-variable/index.md#-1606146105%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [iterator](../../it.unibo.alchemist.loader.variables/-arbitrary-variable/index.md#-1606146105%2FFunctions%2F-267951372)(): [Iterator](https://docs.oracle.com/javase/8/docs/api/java/util/Iterator.html)<[T](../-action/index.md)> |
| [remove](remove.md) | [jvm]<br>abstract fun [remove](remove.md)(node: [Node](../-node/index.md)<[T](../-action/index.md)>): [Neighborhood](index.md)<[T](../-action/index.md)><br>the [Node](../-node/index.md) to remove |
| [size](size.md) | [jvm]<br>abstract fun [size](size.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>the number of neighbors. |
| [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-677603448%2FFunctions%2F-267951372) | [jvm]<br>open fun [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-677603448%2FFunctions%2F-267951372)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[T](../-action/index.md)> |

## Inheritors

| Name |
|---|
| [SimpleNeighborhood](../../it.unibo.alchemist.model.implementations.neighborhoods/-simple-neighborhood/index.md) |
