---
title: assignVarValue
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.expressions.implementations](../index.html)/[AST](index.html)/[assignVarValue](assign-var-value.html)



# assignVarValue



[jvm]\
open fun [assignVarValue](assign-var-value.html)(matches: [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<HashString, [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>>): [AST](index.html)



This method substitutes variables present in matches map with their values. It must involve only node of Typ=Var. The method must also recognize the values type stored in the map (they can be Const or Num).



#### Return



a new ITree containing the instantiated variable



## Parameters


jvm

| | |
|---|---|
| matches | the map with variable values already assigned. |




