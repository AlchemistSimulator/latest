---
title: ITreeNode
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.expressions.interfaces](../index.html)/[ITreeNode](index.html)



# ITreeNode



[jvm]\
interface [ITreeNode](index.html)<[T](index.html)> : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)

Represents an interface for node of the Tree class.



## Parameters


jvm

| | |
|---|---|
| <T> | concentration type |



## Functions


| Name | Summary |
|---|---|
| [getData](get-data.html) | [jvm]<br>abstract fun [getData](get-data.html)(): [T](index.html)<br>the object embedded in this node |
| [getLeftChild](get-left-child.html) | [jvm]<br>abstract fun [getLeftChild](get-left-child.html)(): [ITreeNode](index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)><br>the left child (if any) |
| [getNumberOfChildren](get-number-of-children.html) | [jvm]<br>abstract fun [getNumberOfChildren](get-number-of-children.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>the number of first level children. |
| [getRightChild](get-right-child.html) | [jvm]<br>abstract fun [getRightChild](get-right-child.html)(): [ITreeNode](index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)><br>the righr child (if any) |
| [getType](get-type.html) | [jvm]<br>abstract fun [getType](get-type.html)(): [Type](../../it.unibo.alchemist.expressions.implementations/-type/index.html)<br>the type of this node |
| [getValue](get-value.html) | [jvm]<br>abstract fun [getValue](get-value.html)(mp: [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<HashString, [ITreeNode](index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>>): [T](index.html)<br>the matches map. |
| [toHashString](to-hash-string.html) | [jvm]<br>abstract fun [toHashString](to-hash-string.html)(): HashString<br>Similar to toString(), but returns a HashString. |
| [toString](to-string.html) | [jvm]<br>abstract fun [toString](to-string.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)<br>a String representation of this Object |


## Inheritors


| Name |
|---|
| [ATreeNode](../../it.unibo.alchemist.expressions.implementations/-a-tree-node/index.html) |

