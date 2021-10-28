---
title: it.unibo.alchemist.expressions.implementations
---
//[alchemist](../../index.html)/[it.unibo.alchemist.expressions.implementations](index.html)



# Package it.unibo.alchemist.expressions.implementations



## Types


| Name | Summary |
|---|---|
| [AST](-a-s-t/index.html) | [jvm]<br>class [AST](-a-s-t/index.html) : [ITree](../it.unibo.alchemist.expressions.interfaces/-i-tree/index.html) |
| [ATreeNode](-a-tree-node/index.html) | [jvm]<br>abstract class [ATreeNode](-a-tree-node/index.html)<[T](-a-tree-node/index.html)> : [ITreeNode](../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.html)<[T](../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.html)> <br>concentration type |
| [ComparatorTreeNode](-comparator-tree-node/index.html) | [jvm]<br>class [ComparatorTreeNode](-comparator-tree-node/index.html) : [ATreeNode](-a-tree-node/index.html)<HashString> |
| [ConstTreeNode](-const-tree-node/index.html) | [jvm]<br>open class [ConstTreeNode](-const-tree-node/index.html) : [ATreeNode](-a-tree-node/index.html)<HashString> |
| [Expression](-expression/index.html) | [jvm]<br>class [Expression](-expression/index.html) : [IExpression](../it.unibo.alchemist.expressions.interfaces/-i-expression/index.html) |
| [ExpressionFactory](-expression-factory/index.html) | [jvm]<br>class [ExpressionFactory](-expression-factory/index.html)<br>This utility class provides methods to ease the building and usage of [IExpression](../it.unibo.alchemist.expressions.interfaces/-i-expression/index.html) without parsing. |
| [ListComparator](-list-comparator/index.html) | [jvm]<br>enum [ListComparator](-list-comparator/index.html) |
| [ListComparatorTreeNode](-list-comparator-tree-node/index.html) | [jvm]<br>open class [ListComparatorTreeNode](-list-comparator-tree-node/index.html) : [ATreeNode](-a-tree-node/index.html)<[ListComparator](-list-comparator/index.html)> |
| [ListTreeNode](-list-tree-node/index.html) | [jvm]<br>class [ListTreeNode](-list-tree-node/index.html) : [ATreeNode](-a-tree-node/index.html)<[Set](https://docs.oracle.com/javase/8/docs/api/java/util/Set.html)<[ITreeNode](../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>>> , [Iterable](https://docs.oracle.com/javase/8/docs/api/java/lang/Iterable.html)<[ITreeNode](../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>> |
| [NumTreeNode](-num-tree-node/index.html) | [jvm]<br>class [NumTreeNode](-num-tree-node/index.html) : [ATreeNode](-a-tree-node/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)> |
| [Operator](-operator/index.html) | [jvm]<br>enum [Operator](-operator/index.html) |
| [OperatorTreeNode](-operator-tree-node/index.html) | [jvm]<br>open class [OperatorTreeNode](-operator-tree-node/index.html) : [ATreeNode](-a-tree-node/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)> |
| [Type](-type/index.html) | [jvm]<br>enum [Type](-type/index.html) |
| [UIDNode](-u-i-d-node/index.html) | [jvm]<br>class [UIDNode](-u-i-d-node/index.html) : [ConstTreeNode](-const-tree-node/index.html) |
| [VarTreeNode](-var-tree-node/index.html) | [jvm]<br>class [VarTreeNode](-var-tree-node/index.html) : [ATreeNode](-a-tree-node/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> |

