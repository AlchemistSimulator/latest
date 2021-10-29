//[alchemist](../../../index.md)/[it.unibo.alchemist.expressions.interfaces](../index.md)/[ITreeNode](index.md)

# ITreeNode

[jvm]\
interface [ITreeNode](index.md)<[T](index.md)> : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)

Represents an interface for node of the Tree class.

## Parameters

jvm

| | |
|---|---|
| <T> | concentration type |

## Functions

| Name | Summary |
|---|---|
| [getData](get-data.md) | [jvm]<br>abstract fun [getData](get-data.md)(): [T](index.md)<br>the object embedded in this node |
| [getLeftChild](get-left-child.md) | [jvm]<br>abstract fun [getLeftChild](get-left-child.md)(): [ITreeNode](index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)><br>the left child (if any) |
| [getNumberOfChildren](get-number-of-children.md) | [jvm]<br>abstract fun [getNumberOfChildren](get-number-of-children.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>the number of first level children. |
| [getRightChild](get-right-child.md) | [jvm]<br>abstract fun [getRightChild](get-right-child.md)(): [ITreeNode](index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)><br>the righr child (if any) |
| [getType](get-type.md) | [jvm]<br>abstract fun [getType](get-type.md)(): [Type](../../it.unibo.alchemist.expressions.implementations/-type/index.md)<br>the type of this node |
| [getValue](get-value.md) | [jvm]<br>abstract fun [getValue](get-value.md)(mp: [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<HashString, [ITreeNode](index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>>): [T](index.md)<br>the matches map. |
| [toHashString](to-hash-string.md) | [jvm]<br>abstract fun [toHashString](to-hash-string.md)(): HashString<br>Similar to toString(), but returns a HashString. |
| [toString](to-string.md) | [jvm]<br>abstract fun [toString](to-string.md)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)<br>a String representation of this Object |

## Inheritors

| Name |
|---|
| [ATreeNode](../../it.unibo.alchemist.expressions.implementations/-a-tree-node/index.md) |
