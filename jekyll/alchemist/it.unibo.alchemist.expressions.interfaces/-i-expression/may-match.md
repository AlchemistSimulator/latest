---
title: mayMatch
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.expressions.interfaces](../index.html)/[IExpression](index.html)/[mayMatch](may-match.html)



# mayMatch



[jvm]\
abstract fun [mayMatch](may-match.html)(expr: [IExpression](index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)



This match method test whether or not two expressions might match. It can be used to evaluate dependencies in a general fashion, it does not check if all the relations are satisfied (e.g. if applying the comparators) but makes a sort of "type checking". If you want to compare two templates, this is the way to go.



#### Return



true if this expression can "match" with expr.



## Parameters


jvm

| | |
|---|---|
| expr | the expression to verify the possibility of future matches |




