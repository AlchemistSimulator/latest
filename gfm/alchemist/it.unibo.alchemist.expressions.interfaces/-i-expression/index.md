//[alchemist](../../../index.md)/[it.unibo.alchemist.expressions.interfaces](../index.md)/[IExpression](index.md)

# IExpression

[jvm]\
interface [IExpression](index.md) : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html), [Cloneable](https://docs.oracle.com/javase/8/docs/api/java/lang/Cloneable.html)

## Functions

| Name | Summary |
|---|---|
| [calculate](calculate.md) | [jvm]<br>abstract fun [calculate](calculate.md)(map: [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<HashString, [ITreeNode](../-i-tree-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>>): [ITreeNode](../-i-tree-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)><br>the map of the matches. |
| [getAST](get-a-s-t.md) | [jvm]<br>abstract fun [getAST](get-a-s-t.md)(): [ITree](../-i-tree/index.md)<br>the ast representing the IExpression |
| [getLeftChildren](get-left-children.md) | [jvm]<br>abstract fun [getLeftChildren](get-left-children.md)(): [ITreeNode](../-i-tree-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)><br>the left children of the root element. |
| [getRightChildren](get-right-children.md) | [jvm]<br>abstract fun [getRightChildren](get-right-children.md)(): [ITreeNode](../-i-tree-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)><br>the right children of the root element. |
| [getRootNode](get-root-node.md) | [jvm]<br>abstract fun [getRootNode](get-root-node.md)(): [ITreeNode](../-i-tree-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)><br>the root note of the AST of this expression |
| [getRootNodeData](get-root-node-data.md) | [jvm]<br>abstract fun [getRootNodeData](get-root-node-data.md)(): [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)<br>the first AST Node Data. |
| [getRootNodeType](get-root-node-type.md) | [jvm]<br>abstract fun [getRootNodeType](get-root-node-type.md)(): [Type](../../it.unibo.alchemist.expressions.implementations/-type/index.md)<br>the first AST Node Data. |
| [matches](matches.md) | [jvm]<br>abstract fun [matches](matches.md)(expr: [IExpression](index.md), map: [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<HashString, [ITreeNode](../-i-tree-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Tries to match this expression with expr. |
| [mayMatch](may-match.md) | [jvm]<br>abstract fun [mayMatch](may-match.md)(expr: [IExpression](index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>This match method test whether or not two expressions might match. |
| [syntacticMatch](syntactic-match.md) | [jvm]<br>abstract fun [syntacticMatch](syntactic-match.md)(e: [IExpression](index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Runs a syntactic match against the e. |
| [updateMatchedVar](update-matched-var.md) | [jvm]<br>abstract fun [updateMatchedVar](update-matched-var.md)(map: [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<HashString, [ITreeNode](../-i-tree-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>>): [ITree](../-i-tree/index.md)<br>the matches map |

## Inheritors

| Name |
|---|
| [Expression](../../it.unibo.alchemist.expressions.implementations/-expression/index.md) |
