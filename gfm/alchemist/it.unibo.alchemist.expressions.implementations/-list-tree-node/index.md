//[alchemist](../../../index.md)/[it.unibo.alchemist.expressions.implementations](../index.md)/[ListTreeNode](index.md)

# ListTreeNode

[jvm]\
class [ListTreeNode](index.md) : [ATreeNode](../-a-tree-node/index.md)<[Set](https://docs.oracle.com/javase/8/docs/api/java/util/Set.html)<[ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>>> , [Iterable](https://docs.oracle.com/javase/8/docs/api/java/lang/Iterable.html)<[ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>>

## Constructors

| | |
|---|---|
| [ListTreeNode](-list-tree-node.md) | [jvm]<br>open fun [ListTreeNode](-list-tree-node.md)(data: [Set](https://docs.oracle.com/javase/8/docs/api/java/util/Set.html)<[ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>>)<br>the list which embedded in this node |

## Functions

| Name | Summary |
|---|---|
| [equals](../-a-tree-node/equals.md) | [jvm]<br>open fun [equals](../-a-tree-node/equals.md)(t: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [forEach](index.md#-655675525%2FFunctions%2F-267951372) | [jvm]<br>open fun [forEach](index.md#-655675525%2FFunctions%2F-267951372)(action: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |
| [getData](../-operator-tree-node/index.md#1261515164%2FFunctions%2F-267951372) | [jvm]<br>open fun [getData](../-operator-tree-node/index.md#1261515164%2FFunctions%2F-267951372)(): [T](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.md)<br>the object embedded in this node |
| [getLeftChild](../-a-tree-node/get-left-child.md) | [jvm]<br>open fun [getLeftChild](../-a-tree-node/get-left-child.md)(): [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)><br>the left child (if any) |
| [getNumberOfChildren](../-a-tree-node/get-number-of-children.md) | [jvm]<br>open fun [getNumberOfChildren](../-a-tree-node/get-number-of-children.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>the number of first level children. |
| [getRightChild](../-a-tree-node/get-right-child.md) | [jvm]<br>open fun [getRightChild](../-a-tree-node/get-right-child.md)(): [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)><br>the righr child (if any) |
| [getType](get-type.md) | [jvm]<br>open fun [getType](get-type.md)(): [Type](../-type/index.md)<br>the type of this node |
| [getValue](get-value.md) | [jvm]<br>open fun [getValue](get-value.md)(mp: [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<HashString, [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>>): [Set](https://docs.oracle.com/javase/8/docs/api/java/util/Set.html)<[ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>><br>the matches map. |
| [hashCode](../-a-tree-node/hash-code.md) | [jvm]<br>open fun [hashCode](../-a-tree-node/hash-code.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [iterator](iterator.md) | [jvm]<br>open fun [iterator](iterator.md)(): [Iterator](https://docs.oracle.com/javase/8/docs/api/java/util/Iterator.html)<[ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>> |
| [spliterator](index.md#-677603448%2FFunctions%2F-267951372) | [jvm]<br>open fun [spliterator](index.md#-677603448%2FFunctions%2F-267951372)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[T](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.md)> |
| [toHashString](../-a-tree-node/to-hash-string.md) | [jvm]<br>open fun [toHashString](../-a-tree-node/to-hash-string.md)(): HashString<br>Similar to toString(), but returns a HashString. |
| [toString](to-string.md) | [jvm]<br>open fun [toString](to-string.md)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |
