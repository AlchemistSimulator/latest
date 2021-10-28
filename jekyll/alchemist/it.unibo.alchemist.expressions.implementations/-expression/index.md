---
title: Expression
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.expressions.implementations](../index.html)/[Expression](index.html)



# Expression



[jvm]\
class [Expression](index.html) : [IExpression](../../it.unibo.alchemist.expressions.interfaces/-i-expression/index.html)



## Constructors


| | |
|---|---|
| [Expression](-expression.html) | [jvm]<br>open fun [Expression](-expression.html)(tree: [ITree](../../it.unibo.alchemist.expressions.interfaces/-i-tree/index.html))<br>This constructor does not do any parsing, and thus is much faster than the other one. |
| [Expression](-expression.html) | [jvm]<br>open fun [Expression](-expression.html)(n: [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>)<br>the root node of the expression |
| [Expression](-expression.html) | [jvm]<br>open fun [Expression](-expression.html)(s: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html))<br>This constructor parses the String into an Expression. |


## Functions


| Name | Summary |
|---|---|
| [calculate](calculate.html) | [jvm]<br>open fun [calculate](calculate.html)(map: [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<HashString, [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>>): [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)><br>the map of the matches. |
| [getLeftChildren](get-left-children.html) | [jvm]<br>open fun [getLeftChildren](get-left-children.html)(): [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)><br>the left children of the root element. |
| [getRightChildren](get-right-children.html) | [jvm]<br>open fun [getRightChildren](get-right-children.html)(): [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)><br>the right children of the root element. |
| [getRootNodeData](get-root-node-data.html) | [jvm]<br>open fun [getRootNodeData](get-root-node-data.html)(): [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)<br>the first AST Node Data. |
| [getRootNodeType](get-root-node-type.html) | [jvm]<br>open fun [getRootNodeType](get-root-node-type.html)(): [Type](../-type/index.html)<br>the first AST Node Data. |
| [matches](matches.html) | [jvm]<br>open fun [matches](matches.html)(expr: [IExpression](../../it.unibo.alchemist.expressions.interfaces/-i-expression/index.html), matches: [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<HashString, [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Tries to match this expression with expr. |
| [mayMatch](may-match.html) | [jvm]<br>open fun [mayMatch](may-match.html)(expr: [IExpression](../../it.unibo.alchemist.expressions.interfaces/-i-expression/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>This match method test whether or not two expressions might match. |
| [syntacticMatch](syntactic-match.html) | [jvm]<br>open fun [syntacticMatch](syntactic-match.html)(e: [IExpression](../../it.unibo.alchemist.expressions.interfaces/-i-expression/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Runs a syntactic match against the e. |
| [toString](to-string.html) | [jvm]<br>open fun [toString](to-string.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |
| [updateMatchedVar](update-matched-var.html) | [jvm]<br>open fun [updateMatchedVar](update-matched-var.html)(matches: [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<HashString, [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>>): [ITree](../../it.unibo.alchemist.expressions.interfaces/-i-tree/index.html)<br>the matches map |


## Properties


| Name | Summary |
|---|---|
| [ast](ast.html) | [jvm]<br>private val [ast](ast.html): [ITree](../../it.unibo.alchemist.expressions.interfaces/-i-tree/index.html) |
| [rootNode](root-node.html) | [jvm]<br>private val [rootNode](root-node.html): [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> |

