---
title: Neighborhood
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces](../index.html)/[Neighborhood](index.html)



# Neighborhood



[jvm]\
interface [Neighborhood](index.html)<[T](index.html)> : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html), [Cloneable](https://docs.oracle.com/javase/8/docs/api/java/lang/Cloneable.html), [Iterable](https://docs.oracle.com/javase/8/docs/api/java/lang/Iterable.html)<[Node](../-node/index.html)<[T](../-node/index.html)>> 

The type which describes the concentration of a molecule Interface for a neighborhood. When implementing it in a real class, please remember to correctly implement also the equals method inherited from Object.



## Parameters


jvm

| | |
|---|---|
| <T> | concentration type |



## Functions


| Name | Summary |
|---|---|
| [add](add.html) | [jvm]<br>abstract fun [add](add.html)(node: [Node](../-node/index.html)<[T](../-node/index.html)>): [Neighborhood](index.html)<[T](../-node/index.html)><br>the [Node](../-node/index.html) to add |
| [contains](contains.html) | [jvm]<br>abstract fun [contains](contains.html)(n: [Node](../-node/index.html)<[T](../-node/index.html)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Verifies if a node is contained inside a neighborhood. |
| [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-655675525%2FFunctions%2F-134779887) | [jvm]<br>open fun [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-655675525%2FFunctions%2F-134779887)(action: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |
| [getCenter](get-center.html) | [jvm]<br>abstract fun [getCenter](get-center.html)(): [Node](../-node/index.html)<[T](../-node/index.html)><br>Allows to access the central node. |
| [getNeighborByNumber](get-neighbor-by-number.html) | [jvm]<br>@[Deprecated](https://docs.oracle.com/javase/8/docs/api/java/lang/Deprecated.html)()<br>~~abstract~~ ~~fun~~ [~~getNeighborByNumber~~](get-neighbor-by-number.html)~~(~~~~num~~~~:~~ [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)~~)~~~~:~~ [Node](../-node/index.html)<[T](../-node/index.html)><br>Returns the num-th neighbor. |
| [getNeighbors](get-neighbors.html) | [jvm]<br>abstract fun [getNeighbors](get-neighbors.html)(): ListSet<out [Node](../-node/index.html)<[T](../-node/index.html)>><br>Allows to directly access every node in the neighborhood. |
| [isEmpty](is-empty.html) | [jvm]<br>abstract fun [isEmpty](is-empty.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>true if this neighborhood has no neighbors |
| [iterator](../../it.unibo.alchemist.loader.variables/-arbitrary-variable/index.html#-1606146105%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [iterator](../../it.unibo.alchemist.loader.variables/-arbitrary-variable/index.html#-1606146105%2FFunctions%2F-134779887)(): [Iterator](https://docs.oracle.com/javase/8/docs/api/java/util/Iterator.html)<[T](../-node/index.html)> |
| [remove](remove.html) | [jvm]<br>abstract fun [remove](remove.html)(node: [Node](../-node/index.html)<[T](../-node/index.html)>): [Neighborhood](index.html)<[T](../-node/index.html)><br>the [Node](../-node/index.html) to remove |
| [size](size.html) | [jvm]<br>abstract fun [size](size.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>the number of neighbors. |
| [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-677603448%2FFunctions%2F-134779887) | [jvm]<br>open fun [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-677603448%2FFunctions%2F-134779887)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[T](../-node/index.html)> |


## Inheritors


| Name |
|---|
| [SimpleNeighborhood](../../it.unibo.alchemist.model.implementations.neighborhoods/-simple-neighborhood/index.html) |

