---
title: buildExpression
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.expressions.implementations](../index.html)/[ExpressionFactory](index.html)/[buildExpression](build-expression.html)



# buildExpression



[jvm]\
open fun [buildExpression](build-expression.html)(n: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [IExpression](../../it.unibo.alchemist.expressions.interfaces/-i-expression/index.html)



Given a number, builds a numeric expression.



#### Return



a new expression



## Parameters


jvm

| | |
|---|---|
| n | a numeric value |





[jvm]\
open fun [buildExpression](build-expression.html)(s: HashString): [IExpression](../../it.unibo.alchemist.expressions.interfaces/-i-expression/index.html)

open fun [buildExpression](build-expression.html)(s: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [IExpression](../../it.unibo.alchemist.expressions.interfaces/-i-expression/index.html)



Given a single literal (either variable or constant), builds the corresponding expression.



#### Return



a new expression



## Parameters


jvm

| | |
|---|---|
| s | MUST BE A SINGLE LITERAL |




