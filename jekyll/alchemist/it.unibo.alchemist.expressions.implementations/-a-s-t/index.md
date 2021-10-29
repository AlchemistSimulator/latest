---
title: AST
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.expressions.implementations](../index.html)/[AST](index.html)



# AST



[jvm]\
class [AST](index.html) : [ITree](../../it.unibo.alchemist.expressions.interfaces/-i-tree/index.html)



## Constructors


| | |
|---|---|
| [AST](-a-s-t.html) | [jvm]<br>open fun [AST](-a-s-t.html)(root: [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>)<br>Builds a new AST given its root node. |


## Functions


| Name | Summary |
|---|---|
| [assignVarValue](assign-var-value.html) | [jvm]<br>open fun [assignVarValue](assign-var-value.html)(matches: [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<HashString, [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>>): [AST](index.html)<br>This method substitutes variables present in matches map with their values. |
| [evaluation](evaluation.html) | [jvm]<br>open fun [evaluation](evaluation.html)(matches: [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<HashString, [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>>): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>This evaluates the expression. |
| [getRoot](get-root.html) | [jvm]<br>open fun [getRoot](get-root.html)(): [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)><br>Return the root Node of the tree. |
| [toHashString](to-hash-string.html) | [jvm]<br>open fun [toHashString](to-hash-string.html)(): HashString<br>Similar to toString(), but returns a HashString. |
| [toString](to-string.html) | [jvm]<br>open fun [toString](to-string.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |

