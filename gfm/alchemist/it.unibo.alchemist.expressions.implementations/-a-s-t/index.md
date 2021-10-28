//[alchemist](../../../index.md)/[it.unibo.alchemist.expressions.implementations](../index.md)/[AST](index.md)

# AST

[jvm]\
class [AST](index.md) : [ITree](../../it.unibo.alchemist.expressions.interfaces/-i-tree/index.md)

## Constructors

| | |
|---|---|
| [AST](-a-s-t.md) | [jvm]<br>open fun [AST](-a-s-t.md)(root: [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>)<br>Builds a new AST given its root node. |

## Functions

| Name | Summary |
|---|---|
| [assignVarValue](assign-var-value.md) | [jvm]<br>open fun [assignVarValue](assign-var-value.md)(matches: [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<HashString, [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>>): [AST](index.md)<br>This method substitutes variables present in matches map with their values. |
| [evaluation](evaluation.md) | [jvm]<br>open fun [evaluation](evaluation.md)(matches: [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<HashString, [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>>): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>This evaluates the expression. |
| [getRoot](get-root.md) | [jvm]<br>open fun [getRoot](get-root.md)(): [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)><br>Return the root Node of the tree. |
| [toHashString](to-hash-string.md) | [jvm]<br>open fun [toHashString](to-hash-string.md)(): HashString<br>Similar to toString(), but returns a HashString. |
| [toString](to-string.md) | [jvm]<br>open fun [toString](to-string.md)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |
