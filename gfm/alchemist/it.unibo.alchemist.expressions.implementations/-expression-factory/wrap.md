//[alchemist](../../../index.md)/[it.unibo.alchemist.expressions.implementations](../index.md)/[ExpressionFactory](index.md)/[wrap](wrap.md)

# wrap

[jvm]\
open fun [wrap](wrap.md)(n: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [IExpression](../../it.unibo.alchemist.expressions.interfaces/-i-expression/index.md)

Given a double, creates a NumTreeNode and wraps it into a [ListTreeNode](../-list-tree-node/index.md).

#### Return

an IExpression containing the passed element in a set

## Parameters

jvm

| | |
|---|---|
| n | the node to wrap |

[jvm]\
open fun [wrap](wrap.md)(s: HashString): [IExpression](../../it.unibo.alchemist.expressions.interfaces/-i-expression/index.md)

Given a HashString, creates the corresponding [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.md) and wraps it into a [ListTreeNode](../-list-tree-node/index.md).

#### Return

an IExpression containing the passed element in a set

## Parameters

jvm

| | |
|---|---|
| s | the node to wrap |

[jvm]\
open fun [wrap](wrap.md)(nodes: [Iterable](https://docs.oracle.com/javase/8/docs/api/java/lang/Iterable.html)<[ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>>): [IExpression](../../it.unibo.alchemist.expressions.interfaces/-i-expression/index.md)

Wraps a collection of [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.md) into a new List IExpression.

#### Return

an IExpression containing all the elements in a set

## Parameters

jvm

| | |
|---|---|
| nodes | the nodes to wrap |

[jvm]\
open fun [wrap](wrap.md)(node: [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>): [IExpression](../../it.unibo.alchemist.expressions.interfaces/-i-expression/index.md)

Given a node, wraps it into a [ListTreeNode](../-list-tree-node/index.md).

#### Return

an IExpression containing the passed element in a set

## Parameters

jvm

| | |
|---|---|
| node | the node to wrap |
