---
title: matches
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.expressions.interfaces](../index.html)/[IExpression](index.html)/[matches](matches.html)



# matches



[jvm]\
abstract fun [matches](matches.html)(expr: [IExpression](index.html), map: [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<HashString, [ITreeNode](../-i-tree-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)



Tries to match this expression with expr. The matching rules are: (i) a variable matches everything; (ii) a constant value matches an identical constant value; (iii) a number matches an identical number or an operator, (iv) operators match everything but constants, (v) comparators match numbers and operators (verifying the values); (vi) expr type can't be comparator; (vii) add and rem operators work only with lists.



#### Return



true if this expression can "match" with expr.



## Parameters


jvm

| | |
|---|---|
| expr | the expression to match |
| map | the matches map |




