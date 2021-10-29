---
title: wrap
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.expressions.implementations](../index.html)/[ExpressionFactory](index.html)/[wrap](wrap.html)



# wrap



[jvm]\
open fun [wrap](wrap.html)(n: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [IExpression](../../it.unibo.alchemist.expressions.interfaces/-i-expression/index.html)



Given a double, creates a NumTreeNode and wraps it into a [ListTreeNode](../-list-tree-node/index.html).



#### Return



an IExpression containing the passed element in a set



## Parameters


jvm

| | |
|---|---|
| n | the node to wrap |





[jvm]\
open fun [wrap](wrap.html)(s: HashString): [IExpression](../../it.unibo.alchemist.expressions.interfaces/-i-expression/index.html)



Given a HashString, creates the corresponding [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.html) and wraps it into a [ListTreeNode](../-list-tree-node/index.html).



#### Return



an IExpression containing the passed element in a set



## Parameters


jvm

| | |
|---|---|
| s | the node to wrap |





[jvm]\
open fun [wrap](wrap.html)(nodes: [Iterable](https://docs.oracle.com/javase/8/docs/api/java/lang/Iterable.html)<[ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>>): [IExpression](../../it.unibo.alchemist.expressions.interfaces/-i-expression/index.html)



Wraps a collection of [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.html) into a new List IExpression.



#### Return



an IExpression containing all the elements in a set



## Parameters


jvm

| | |
|---|---|
| nodes | the nodes to wrap |





[jvm]\
open fun [wrap](wrap.html)(node: [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>): [IExpression](../../it.unibo.alchemist.expressions.interfaces/-i-expression/index.html)



Given a node, wraps it into a [ListTreeNode](../-list-tree-node/index.html).



#### Return



an IExpression containing the passed element in a set



## Parameters


jvm

| | |
|---|---|
| node | the node to wrap |




