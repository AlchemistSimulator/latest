---
title: matches
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces](../index.html)/[ILsaMolecule](index.html)/[matches](matches.html)



# matches



[jvm]\
abstract fun [matches](matches.html)(mol: [ILsaMolecule](index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)



#### Return



true if the two molecules match



## Parameters


jvm

| | |
|---|---|
| mol | the LsaMolecule to try to match with. |





[jvm]\
abstract fun [matches](matches.html)(mol: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<out [IExpression](../../it.unibo.alchemist.expressions.interfaces/-i-expression/index.html)>, duplicateVariables: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)



#### Return



true if the two molecules match



## Parameters


jvm

| | |
|---|---|
| mol | the LsaMolecule to try to match with |
| duplicateVariables | if true, the matching of variables reused within the same tuple is enabled |




