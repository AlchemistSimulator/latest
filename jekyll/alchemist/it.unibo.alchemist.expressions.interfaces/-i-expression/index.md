---
title: IExpression
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.expressions.interfaces](../index.html)/[IExpression](index.html)



# IExpression



[jvm]\
interface [IExpression](index.html) : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html), [Cloneable](https://docs.oracle.com/javase/8/docs/api/java/lang/Cloneable.html)



## Functions


| Name | Summary |
|---|---|
| [calculate](calculate.html) | [jvm]<br>abstract fun [calculate](calculate.html)(map: [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<HashString, [ITreeNode](../-i-tree-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>>): [ITreeNode](../-i-tree-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)><br>the map of the matches. |
| [getAST](get-a-s-t.html) | [jvm]<br>abstract fun [getAST](get-a-s-t.html)(): [ITree](../-i-tree/index.html)<br>the ast representing the IExpression |
| [getLeftChildren](get-left-children.html) | [jvm]<br>abstract fun [getLeftChildren](get-left-children.html)(): [ITreeNode](../-i-tree-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)><br>the left children of the root element. |
| [getRightChildren](get-right-children.html) | [jvm]<br>abstract fun [getRightChildren](get-right-children.html)(): [ITreeNode](../-i-tree-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)><br>the right children of the root element. |
| [getRootNode](get-root-node.html) | [jvm]<br>abstract fun [getRootNode](get-root-node.html)(): [ITreeNode](../-i-tree-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)><br>the root note of the AST of this expression |
| [getRootNodeData](get-root-node-data.html) | [jvm]<br>abstract fun [getRootNodeData](get-root-node-data.html)(): [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)<br>the first AST Node Data. |
| [getRootNodeType](get-root-node-type.html) | [jvm]<br>abstract fun [getRootNodeType](get-root-node-type.html)(): [Type](../../it.unibo.alchemist.expressions.implementations/-type/index.html)<br>the first AST Node Data. |
| [matches](matches.html) | [jvm]<br>abstract fun [matches](matches.html)(expr: [IExpression](index.html), map: [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<HashString, [ITreeNode](../-i-tree-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Tries to match this expression with expr. |
| [mayMatch](may-match.html) | [jvm]<br>abstract fun [mayMatch](may-match.html)(expr: [IExpression](index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>This match method test whether or not two expressions might match. |
| [syntacticMatch](syntactic-match.html) | [jvm]<br>abstract fun [syntacticMatch](syntactic-match.html)(e: [IExpression](index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Runs a syntactic match against the e. |
| [updateMatchedVar](update-matched-var.html) | [jvm]<br>abstract fun [updateMatchedVar](update-matched-var.html)(map: [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<HashString, [ITreeNode](../-i-tree-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>>): [ITree](../-i-tree/index.html)<br>the matches map |


## Inheritors


| Name |
|---|
| [Expression](../../it.unibo.alchemist.expressions.implementations/-expression/index.html) |

