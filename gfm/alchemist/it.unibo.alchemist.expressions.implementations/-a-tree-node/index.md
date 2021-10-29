//[alchemist](../../../index.md)/[it.unibo.alchemist.expressions.implementations](../index.md)/[ATreeNode](index.md)

# ATreeNode

[jvm]\
abstract class [ATreeNode](index.md)<[T](index.md)> : [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.md)<[T](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.md)>

## Parameters

jvm

| | |
|---|---|
| <T> | concentration type |

## Constructors

| | |
|---|---|
| [ATreeNode](-a-tree-node.md) | [jvm]<br>open fun [ATreeNode](-a-tree-node.md)(dat: [T](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.md), l: [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, r: [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>)<br>Builds the internals of a tree node. |

## Functions

| Name | Summary |
|---|---|
| [equals](equals.md) | [jvm]<br>open fun [equals](equals.md)(t: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [getLeftChild](get-left-child.md) | [jvm]<br>open fun [getLeftChild](get-left-child.md)(): [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)><br>the left child (if any) |
| [getNumberOfChildren](get-number-of-children.md) | [jvm]<br>open fun [getNumberOfChildren](get-number-of-children.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>the number of first level children. |
| [getRightChild](get-right-child.md) | [jvm]<br>open fun [getRightChild](get-right-child.md)(): [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)><br>the righr child (if any) |
| [getType](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/get-type.md) | [jvm]<br>abstract fun [getType](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/get-type.md)(): [Type](../-type/index.md)<br>the type of this node |
| [getValue](get-value.md) | [jvm]<br>abstract fun [getValue](get-value.md)(mp: [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<HashString, [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>>): [T](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.md)<br>the matches map. |
| [hashCode](hash-code.md) | [jvm]<br>open fun [hashCode](hash-code.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [toHashString](to-hash-string.md) | [jvm]<br>open fun [toHashString](to-hash-string.md)(): HashString<br>Similar to toString(), but returns a HashString. |
| [toString](to-string.md) | [jvm]<br>abstract fun [toString](to-string.md)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |

## Properties

| Name | Summary |
|---|---|
| [data](data.md) | [jvm]<br>private val [data](data.md): [T](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.md) |

## Inheritors

| Name |
|---|
| [ConstTreeNode](../-const-tree-node/index.md) |
| [VarTreeNode](../-var-tree-node/index.md) |
| [ComparatorTreeNode](../-comparator-tree-node/index.md) |
| [ListTreeNode](../-list-tree-node/index.md) |
| [NumTreeNode](../-num-tree-node/index.md) |
| [ListComparatorTreeNode](../-list-comparator-tree-node/index.md) |
| [OperatorTreeNode](../-operator-tree-node/index.md) |
