---
title: OperatorTreeNode
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.expressions.implementations](../index.html)/[OperatorTreeNode](index.html)



# OperatorTreeNode



[jvm]\
open class [OperatorTreeNode](index.html) : [ATreeNode](../-a-tree-node/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>



## Constructors


| | |
|---|---|
| [OperatorTreeNode](-operator-tree-node.html) | [jvm]<br>open fun [OperatorTreeNode](-operator-tree-node.html)(op: [Operator](../-operator/index.html), left: [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, right: [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>)<br>the operator |


## Functions


| Name | Summary |
|---|---|
| [equals](../-a-tree-node/equals.html) | [jvm]<br>open fun [equals](../-a-tree-node/equals.html)(t: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [getData](index.html#1261515164%2FFunctions%2F-134779887) | [jvm]<br>open fun [getData](index.html#1261515164%2FFunctions%2F-134779887)(): [T](../-a-tree-node/index.html)<br>the object embedded in this node |
| [getLeftChild](../-a-tree-node/get-left-child.html) | [jvm]<br>open fun [getLeftChild](../-a-tree-node/get-left-child.html)(): [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)><br>the left child (if any) |
| [getNumberOfChildren](../-a-tree-node/get-number-of-children.html) | [jvm]<br>open fun [getNumberOfChildren](../-a-tree-node/get-number-of-children.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>the number of first level children. |
| [getRightChild](../-a-tree-node/get-right-child.html) | [jvm]<br>open fun [getRightChild](../-a-tree-node/get-right-child.html)(): [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)><br>the righr child (if any) |
| [getType](get-type.html) | [jvm]<br>open fun [getType](get-type.html)(): [Type](../-type/index.html)<br>the type of this node |
| [getValue](get-value.html) | [jvm]<br>open fun [getValue](get-value.html)(matches: [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<HashString, [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>>): [Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)<br>the matches map. |
| [hashCode](../-a-tree-node/hash-code.html) | [jvm]<br>open fun [hashCode](../-a-tree-node/hash-code.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [toHashString](../-a-tree-node/to-hash-string.html) | [jvm]<br>open fun [toHashString](../-a-tree-node/to-hash-string.html)(): HashString<br>Similar to toString(), but returns a HashString. |
| [toString](to-string.html) | [jvm]<br>open fun [toString](to-string.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |


## Properties


| Name | Summary |
|---|---|
| [operator](operator.html) | [jvm]<br>private val [operator](operator.html): [Operator](../-operator/index.html) |

