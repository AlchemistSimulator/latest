//[alchemist](../../../index.md)/[it.unibo.alchemist.expressions.implementations](../index.md)/[Expression](index.md)/[Expression](-expression.md)

# Expression

[jvm]\
open fun [Expression](-expression.md)(tree: [ITree](../../it.unibo.alchemist.expressions.interfaces/-i-tree/index.md))

This constructor does not do any parsing, and thus is much faster than the other one.

## Parameters

jvm

| | |
|---|---|
| tree | the ITree which represents this Expression |

[jvm]\
open fun [Expression](-expression.md)(n: [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>)

## Parameters

jvm

| | |
|---|---|
| n | the root node of the expression |

[jvm]\
open fun [Expression](-expression.md)(s: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html))

This constructor parses the String into an Expression. Due to the parsing operation, it is slow compared to the other one, and should be used only in the first initialization phase.

## Parameters

jvm

| | |
|---|---|
| s | The String representing the expression |
