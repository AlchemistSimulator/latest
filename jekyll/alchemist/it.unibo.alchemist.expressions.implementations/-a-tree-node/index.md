---
title: ATreeNode
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.expressions.implementations](../index.html)/[ATreeNode](index.html)



# ATreeNode



[jvm]\
abstract class [ATreeNode](index.html)<[T](index.html)> : [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.html)<[T](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.html)>



## Parameters


jvm

| | |
|---|---|
| <T> | concentration type |



## Constructors


| | |
|---|---|
| [ATreeNode](-a-tree-node.html) | [jvm]<br>open fun [ATreeNode](-a-tree-node.html)(dat: [T](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.html), l: [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, r: [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>)<br>Builds the internals of a tree node. |


## Functions


| Name | Summary |
|---|---|
| [equals](equals.html) | [jvm]<br>open fun [equals](equals.html)(t: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [getLeftChild](get-left-child.html) | [jvm]<br>open fun [getLeftChild](get-left-child.html)(): [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)><br>the left child (if any) |
| [getNumberOfChildren](get-number-of-children.html) | [jvm]<br>open fun [getNumberOfChildren](get-number-of-children.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>the number of first level children. |
| [getRightChild](get-right-child.html) | [jvm]<br>open fun [getRightChild](get-right-child.html)(): [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)><br>the righr child (if any) |
| [getType](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/get-type.html) | [jvm]<br>abstract fun [getType](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/get-type.html)(): [Type](../-type/index.html)<br>the type of this node |
| [getValue](get-value.html) | [jvm]<br>abstract fun [getValue](get-value.html)(mp: [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<HashString, [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>>): [T](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.html)<br>the matches map. |
| [hashCode](hash-code.html) | [jvm]<br>open fun [hashCode](hash-code.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [toHashString](to-hash-string.html) | [jvm]<br>open fun [toHashString](to-hash-string.html)(): HashString<br>Similar to toString(), but returns a HashString. |
| [toString](to-string.html) | [jvm]<br>abstract fun [toString](to-string.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |


## Properties


| Name | Summary |
|---|---|
| [data](data.html) | [jvm]<br>private val [data](data.html): [T](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.html) |


## Inheritors


| Name |
|---|
| [ConstTreeNode](../-const-tree-node/index.html) |
| [VarTreeNode](../-var-tree-node/index.html) |
| [ComparatorTreeNode](../-comparator-tree-node/index.html) |
| [ListTreeNode](../-list-tree-node/index.html) |
| [NumTreeNode](../-num-tree-node/index.html) |
| [ListComparatorTreeNode](../-list-comparator-tree-node/index.html) |
| [OperatorTreeNode](../-operator-tree-node/index.html) |

