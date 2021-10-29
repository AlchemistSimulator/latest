//[alchemist](../../../index.md)/[it.unibo.alchemist.expressions.implementations](../index.md)/[UIDNode](index.md)

# UIDNode

[jvm]\
class [UIDNode](index.md) : [ConstTreeNode](../-const-tree-node/index.md)

## Constructors

| | |
|---|---|
| [UIDNode](-u-i-d-node.md) | [jvm]<br>open fun [UIDNode](-u-i-d-node.md)(fs: HashString)<br>Builds a new UUID node. |

## Functions

| Name | Summary |
|---|---|
| [equals](../-a-tree-node/equals.md) | [jvm]<br>open fun [equals](../-a-tree-node/equals.md)(t: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [getData](../-operator-tree-node/index.md#1261515164%2FFunctions%2F-267951372) | [jvm]<br>open fun [getData](../-operator-tree-node/index.md#1261515164%2FFunctions%2F-267951372)(): [T](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.md)<br>the object embedded in this node |
| [getLeftChild](../-a-tree-node/get-left-child.md) | [jvm]<br>open fun [getLeftChild](../-a-tree-node/get-left-child.md)(): [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)><br>the left child (if any) |
| [getNumberOfChildren](../-a-tree-node/get-number-of-children.md) | [jvm]<br>open fun [getNumberOfChildren](../-a-tree-node/get-number-of-children.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>the number of first level children. |
| [getRightChild](../-a-tree-node/get-right-child.md) | [jvm]<br>open fun [getRightChild](../-a-tree-node/get-right-child.md)(): [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)><br>the righr child (if any) |
| [getType](../-const-tree-node/get-type.md) | [jvm]<br>open fun [getType](../-const-tree-node/get-type.md)(): [Type](../-type/index.md)<br>the type of this node |
| [getValue](../-a-tree-node/get-value.md) | [jvm]<br>abstract fun [getValue](../-a-tree-node/get-value.md)(mp: [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<HashString, [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>>): [T](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.md)<br>open fun [getValue](get-value.md)(mp: [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<HashString, [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>>): HashString<br>the matches map. |
| [hashCode](../-a-tree-node/hash-code.md) | [jvm]<br>open fun [hashCode](../-a-tree-node/hash-code.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [toHashString](to-hash-string.md) | [jvm]<br>open fun [toHashString](to-hash-string.md)(): HashString<br>Similar to toString(), but returns a HashString. |
| [toString](to-string.md) | [jvm]<br>open fun [toString](to-string.md)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |
