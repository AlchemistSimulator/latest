---
title: ITree
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.expressions.interfaces](../index.html)/[ITree](index.html)



# ITree



[jvm]\
interface [ITree](index.html) : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)

Represents a Tree of Objects(Node) of generic type T. The Tree is represented as a single rootElement which points to a List



## Functions


| Name | Summary |
|---|---|
| [assignVarValue](assign-var-value.html) | [jvm]<br>abstract fun [assignVarValue](assign-var-value.html)(matches: [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<HashString, [ITreeNode](../-i-tree-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>>): [ITree](index.html)<br>This method substitutes variables present in matches map with their values. |
| [evaluation](evaluation.html) | [jvm]<br>abstract fun [evaluation](evaluation.html)(matches: [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<HashString, [ITreeNode](../-i-tree-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>>): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>This evaluates the expression. |
| [getRoot](get-root.html) | [jvm]<br>abstract fun [getRoot](get-root.html)(): [ITreeNode](../-i-tree-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)><br>Return the root Node of the tree. |
| [toHashString](to-hash-string.html) | [jvm]<br>abstract fun [toHashString](to-hash-string.html)(): HashString<br>Similar to toString(), but returns a HashString. |


## Inheritors


| Name |
|---|
| [AST](../../it.unibo.alchemist.expressions.implementations/-a-s-t/index.html) |

