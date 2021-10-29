---
title: UIDNode
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.expressions.implementations](../index.html)/[UIDNode](index.html)



# UIDNode



[jvm]\
class [UIDNode](index.html) : [ConstTreeNode](../-const-tree-node/index.html)



## Constructors


| | |
|---|---|
| [UIDNode](-u-i-d-node.html) | [jvm]<br>open fun [UIDNode](-u-i-d-node.html)(fs: HashString)<br>Builds a new UUID node. |


## Functions


| Name | Summary |
|---|---|
| [equals](../-a-tree-node/equals.html) | [jvm]<br>open fun [equals](../-a-tree-node/equals.html)(t: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [getData](../-operator-tree-node/index.html#1261515164%2FFunctions%2F-134779887) | [jvm]<br>open fun [getData](../-operator-tree-node/index.html#1261515164%2FFunctions%2F-134779887)(): [T](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.html)<br>the object embedded in this node |
| [getLeftChild](../-a-tree-node/get-left-child.html) | [jvm]<br>open fun [getLeftChild](../-a-tree-node/get-left-child.html)(): [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)><br>the left child (if any) |
| [getNumberOfChildren](../-a-tree-node/get-number-of-children.html) | [jvm]<br>open fun [getNumberOfChildren](../-a-tree-node/get-number-of-children.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>the number of first level children. |
| [getRightChild](../-a-tree-node/get-right-child.html) | [jvm]<br>open fun [getRightChild](../-a-tree-node/get-right-child.html)(): [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)><br>the righr child (if any) |
| [getType](../-const-tree-node/get-type.html) | [jvm]<br>open fun [getType](../-const-tree-node/get-type.html)(): [Type](../-type/index.html)<br>the type of this node |
| [getValue](../-a-tree-node/get-value.html) | [jvm]<br>abstract fun [getValue](../-a-tree-node/get-value.html)(mp: [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<HashString, [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>>): [T](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.html)<br>open fun [getValue](get-value.html)(mp: [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<HashString, [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>>): HashString<br>the matches map. |
| [hashCode](../-a-tree-node/hash-code.html) | [jvm]<br>open fun [hashCode](../-a-tree-node/hash-code.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [toHashString](to-hash-string.html) | [jvm]<br>open fun [toHashString](to-hash-string.html)(): HashString<br>Similar to toString(), but returns a HashString. |
| [toString](to-string.html) | [jvm]<br>open fun [toString](to-string.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |

