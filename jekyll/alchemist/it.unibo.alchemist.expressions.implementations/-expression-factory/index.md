---
title: ExpressionFactory
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.expressions.implementations](../index.html)/[ExpressionFactory](index.html)



# ExpressionFactory



[jvm]\
class [ExpressionFactory](index.html)

This utility class provides methods to ease the building and usage of [IExpression](../../it.unibo.alchemist.expressions.interfaces/-i-expression/index.html) without parsing.



## Functions


| Name | Summary |
|---|---|
| [buildComplexGroundExpression](build-complex-ground-expression.html) | [jvm]<br>open fun [buildComplexGroundExpression](build-complex-ground-expression.html)(s: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [IExpression](../../it.unibo.alchemist.expressions.interfaces/-i-expression/index.html)<br>Given a single literal (either variable or constant), builds the corresponding expression. |
| [buildExpression](build-expression.html) | [jvm]<br>open fun [buildExpression](build-expression.html)(n: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [IExpression](../../it.unibo.alchemist.expressions.interfaces/-i-expression/index.html)<br>Given a number, builds a numeric expression.<br>[jvm]<br>open fun [buildExpression](build-expression.html)(s: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [IExpression](../../it.unibo.alchemist.expressions.interfaces/-i-expression/index.html)<br>open fun [buildExpression](build-expression.html)(s: HashString): [IExpression](../../it.unibo.alchemist.expressions.interfaces/-i-expression/index.html)<br>Given a single literal (either variable or constant), builds the corresponding expression. |
| [buildLiteralNode](build-literal-node.html) | [jvm]<br>open fun [buildLiteralNode](build-literal-node.html)(s: HashString): [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)><br>Given a single literal (either variable or constant), builds the corresponding [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.html). |
| [wrap](wrap.html) | [jvm]<br>open fun [wrap](wrap.html)(n: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [IExpression](../../it.unibo.alchemist.expressions.interfaces/-i-expression/index.html)<br>Given a double, creates a NumTreeNode and wraps it into a [ListTreeNode](../-list-tree-node/index.html).<br>[jvm]<br>open fun [wrap](wrap.html)(node: [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>): [IExpression](../../it.unibo.alchemist.expressions.interfaces/-i-expression/index.html)<br>Given a node, wraps it into a [ListTreeNode](../-list-tree-node/index.html).<br>[jvm]<br>open fun [wrap](wrap.html)(nodes: [Iterable](https://docs.oracle.com/javase/8/docs/api/java/lang/Iterable.html)<[ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>>): [IExpression](../../it.unibo.alchemist.expressions.interfaces/-i-expression/index.html)<br>Wraps a collection of [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.html) into a new List IExpression.<br>[jvm]<br>open fun [wrap](wrap.html)(s: HashString): [IExpression](../../it.unibo.alchemist.expressions.interfaces/-i-expression/index.html)<br>Given a HashString, creates the corresponding [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.html) and wraps it into a [ListTreeNode](../-list-tree-node/index.html). |

