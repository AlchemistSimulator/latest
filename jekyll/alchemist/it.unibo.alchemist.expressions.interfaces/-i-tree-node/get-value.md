---
title: getValue
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.expressions.interfaces](../index.html)/[ITreeNode](index.html)/[getValue](get-value.html)



# getValue



[jvm]\
abstract fun [getValue](get-value.html)(mp: [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<HashString, [ITreeNode](index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>>): [T](index.html)



#### Return



the value of the Node. (Double if it's a Num or a Var of type Num, String if it's a Const or a Var of type Const) the method return null if there are some variable not yet allocated in the expression.



## Parameters


jvm

| | |
|---|---|
| mp | the matches map. If it is not available or not required (e.g. for evaluating a number or a const), then null values can be used |




