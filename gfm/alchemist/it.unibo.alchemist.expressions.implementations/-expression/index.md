//[alchemist](../../../index.md)/[it.unibo.alchemist.expressions.implementations](../index.md)/[Expression](index.md)

# Expression

[jvm]\
class [Expression](index.md) : [IExpression](../../it.unibo.alchemist.expressions.interfaces/-i-expression/index.md)

## Constructors

| | |
|---|---|
| [Expression](-expression.md) | [jvm]<br>open fun [Expression](-expression.md)(tree: [ITree](../../it.unibo.alchemist.expressions.interfaces/-i-tree/index.md))<br>This constructor does not do any parsing, and thus is much faster than the other one. |
| [Expression](-expression.md) | [jvm]<br>open fun [Expression](-expression.md)(n: [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>)<br>the root node of the expression |
| [Expression](-expression.md) | [jvm]<br>open fun [Expression](-expression.md)(s: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html))<br>This constructor parses the String into an Expression. |

## Functions

| Name | Summary |
|---|---|
| [calculate](calculate.md) | [jvm]<br>open fun [calculate](calculate.md)(map: [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<HashString, [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>>): [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)><br>the map of the matches. |
| [getLeftChildren](get-left-children.md) | [jvm]<br>open fun [getLeftChildren](get-left-children.md)(): [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)><br>the left children of the root element. |
| [getRightChildren](get-right-children.md) | [jvm]<br>open fun [getRightChildren](get-right-children.md)(): [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)><br>the right children of the root element. |
| [getRootNodeData](get-root-node-data.md) | [jvm]<br>open fun [getRootNodeData](get-root-node-data.md)(): [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)<br>the first AST Node Data. |
| [getRootNodeType](get-root-node-type.md) | [jvm]<br>open fun [getRootNodeType](get-root-node-type.md)(): [Type](../-type/index.md)<br>the first AST Node Data. |
| [matches](matches.md) | [jvm]<br>open fun [matches](matches.md)(expr: [IExpression](../../it.unibo.alchemist.expressions.interfaces/-i-expression/index.md), matches: [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<HashString, [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Tries to match this expression with expr. |
| [mayMatch](may-match.md) | [jvm]<br>open fun [mayMatch](may-match.md)(expr: [IExpression](../../it.unibo.alchemist.expressions.interfaces/-i-expression/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>This match method test whether or not two expressions might match. |
| [syntacticMatch](syntactic-match.md) | [jvm]<br>open fun [syntacticMatch](syntactic-match.md)(e: [IExpression](../../it.unibo.alchemist.expressions.interfaces/-i-expression/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Runs a syntactic match against the e. |
| [toString](to-string.md) | [jvm]<br>open fun [toString](to-string.md)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |
| [updateMatchedVar](update-matched-var.md) | [jvm]<br>open fun [updateMatchedVar](update-matched-var.md)(matches: [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<HashString, [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>>): [ITree](../../it.unibo.alchemist.expressions.interfaces/-i-tree/index.md)<br>the matches map |

## Properties

| Name | Summary |
|---|---|
| [ast](ast.md) | [jvm]<br>private val [ast](ast.md): [ITree](../../it.unibo.alchemist.expressions.interfaces/-i-tree/index.md) |
| [rootNode](root-node.md) | [jvm]<br>private val [rootNode](root-node.md): [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> |
