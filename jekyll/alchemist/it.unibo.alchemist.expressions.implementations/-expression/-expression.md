---
title: Expression
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.expressions.implementations](../index.html)/[Expression](index.html)/[Expression](-expression.html)



# Expression



[jvm]\
open fun [Expression](-expression.html)(tree: [ITree](../../it.unibo.alchemist.expressions.interfaces/-i-tree/index.html))



This constructor does not do any parsing, and thus is much faster than the other one.



## Parameters


jvm

| | |
|---|---|
| tree | the ITree which represents this Expression |





[jvm]\
open fun [Expression](-expression.html)(n: [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>)



## Parameters


jvm

| | |
|---|---|
| n | the root node of the expression |





[jvm]\
open fun [Expression](-expression.html)(s: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html))



This constructor parses the String into an Expression. Due to the parsing operation, it is slow compared to the other one, and should be used only in the first initialization phase.



## Parameters


jvm

| | |
|---|---|
| s | The String representing the expression |




