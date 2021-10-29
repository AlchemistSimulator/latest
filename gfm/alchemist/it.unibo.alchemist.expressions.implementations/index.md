//[alchemist](../../index.md)/[it.unibo.alchemist.expressions.implementations](index.md)

# Package it.unibo.alchemist.expressions.implementations

## Types

| Name | Summary |
|---|---|
| [AST](-a-s-t/index.md) | [jvm]<br>class [AST](-a-s-t/index.md) : [ITree](../it.unibo.alchemist.expressions.interfaces/-i-tree/index.md) |
| [ATreeNode](-a-tree-node/index.md) | [jvm]<br>abstract class [ATreeNode](-a-tree-node/index.md)<[T](-a-tree-node/index.md)> : [ITreeNode](../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.md)<[T](../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.md)> <br>concentration type |
| [ComparatorTreeNode](-comparator-tree-node/index.md) | [jvm]<br>class [ComparatorTreeNode](-comparator-tree-node/index.md) : [ATreeNode](-a-tree-node/index.md)<HashString> |
| [ConstTreeNode](-const-tree-node/index.md) | [jvm]<br>open class [ConstTreeNode](-const-tree-node/index.md) : [ATreeNode](-a-tree-node/index.md)<HashString> |
| [Expression](-expression/index.md) | [jvm]<br>class [Expression](-expression/index.md) : [IExpression](../it.unibo.alchemist.expressions.interfaces/-i-expression/index.md) |
| [ExpressionFactory](-expression-factory/index.md) | [jvm]<br>class [ExpressionFactory](-expression-factory/index.md)<br>This utility class provides methods to ease the building and usage of [IExpression](../it.unibo.alchemist.expressions.interfaces/-i-expression/index.md) without parsing. |
| [ListComparator](-list-comparator/index.md) | [jvm]<br>enum [ListComparator](-list-comparator/index.md) |
| [ListComparatorTreeNode](-list-comparator-tree-node/index.md) | [jvm]<br>open class [ListComparatorTreeNode](-list-comparator-tree-node/index.md) : [ATreeNode](-a-tree-node/index.md)<[ListComparator](-list-comparator/index.md)> |
| [ListTreeNode](-list-tree-node/index.md) | [jvm]<br>class [ListTreeNode](-list-tree-node/index.md) : [ATreeNode](-a-tree-node/index.md)<[Set](https://docs.oracle.com/javase/8/docs/api/java/util/Set.html)<[ITreeNode](../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>>> , [Iterable](https://docs.oracle.com/javase/8/docs/api/java/lang/Iterable.html)<[ITreeNode](../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>> |
| [NumTreeNode](-num-tree-node/index.md) | [jvm]<br>class [NumTreeNode](-num-tree-node/index.md) : [ATreeNode](-a-tree-node/index.md)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)> |
| [Operator](-operator/index.md) | [jvm]<br>enum [Operator](-operator/index.md) |
| [OperatorTreeNode](-operator-tree-node/index.md) | [jvm]<br>open class [OperatorTreeNode](-operator-tree-node/index.md) : [ATreeNode](-a-tree-node/index.md)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)> |
| [Type](-type/index.md) | [jvm]<br>enum [Type](-type/index.md) |
| [UIDNode](-u-i-d-node/index.md) | [jvm]<br>class [UIDNode](-u-i-d-node/index.md) : [ConstTreeNode](-const-tree-node/index.md) |
| [VarTreeNode](-var-tree-node/index.md) | [jvm]<br>class [VarTreeNode](-var-tree-node/index.md) : [ATreeNode](-a-tree-node/index.md)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> |
