//[alchemist](../../../index.md)/[it.unibo.alchemist.expressions.implementations](../index.md)/[ExpressionFactory](index.md)/[buildExpression](build-expression.md)

# buildExpression

[jvm]\
open fun [buildExpression](build-expression.md)(n: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [IExpression](../../it.unibo.alchemist.expressions.interfaces/-i-expression/index.md)

Given a number, builds a numeric expression.

#### Return

a new expression

## Parameters

jvm

| | |
|---|---|
| n | a numeric value |

[jvm]\
open fun [buildExpression](build-expression.md)(s: HashString): [IExpression](../../it.unibo.alchemist.expressions.interfaces/-i-expression/index.md)

open fun [buildExpression](build-expression.md)(s: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [IExpression](../../it.unibo.alchemist.expressions.interfaces/-i-expression/index.md)

Given a single literal (either variable or constant), builds the corresponding expression.

#### Return

a new expression

## Parameters

jvm

| | |
|---|---|
| s | MUST BE A SINGLE LITERAL |
