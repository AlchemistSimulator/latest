//[alchemist](../../../index.md)/[it.unibo.alchemist.expressions.interfaces](../index.md)/[ITree](index.md)

# ITree

[jvm]\
interface [ITree](index.md) : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)

Represents a Tree of Objects(Node) of generic type T. The Tree is represented as a single rootElement which points to a List

## Functions

| Name | Summary |
|---|---|
| [assignVarValue](assign-var-value.md) | [jvm]<br>abstract fun [assignVarValue](assign-var-value.md)(matches: [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<HashString, [ITreeNode](../-i-tree-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>>): [ITree](index.md)<br>This method substitutes variables present in matches map with their values. |
| [evaluation](evaluation.md) | [jvm]<br>abstract fun [evaluation](evaluation.md)(matches: [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<HashString, [ITreeNode](../-i-tree-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>>): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>This evaluates the expression. |
| [getRoot](get-root.md) | [jvm]<br>abstract fun [getRoot](get-root.md)(): [ITreeNode](../-i-tree-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)><br>Return the root Node of the tree. |
| [toHashString](to-hash-string.md) | [jvm]<br>abstract fun [toHashString](to-hash-string.md)(): HashString<br>Similar to toString(), but returns a HashString. |

## Inheritors

| Name |
|---|
| [AST](../../it.unibo.alchemist.expressions.implementations/-a-s-t/index.md) |
