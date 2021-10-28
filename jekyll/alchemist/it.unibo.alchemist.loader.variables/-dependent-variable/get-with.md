---
title: getWith
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.loader.variables](../index.html)/[DependentVariable](index.html)/[getWith](get-with.html)



# getWith



[jvm]\
abstract fun [getWith](get-with.html)(variables: [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<[String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>): [V](../-printable-variable/index.html)



Given the current controlled variables, computes the current values for this variable.



#### Return



the value for this value



## Parameters


jvm

| | |
|---|---|
| variables | a mapping between variable names and values |



#### Throws


| | |
|---|---|
| [java.lang.IllegalStateException](https://docs.oracle.com/javase/8/docs/api/java/lang/IllegalStateException.html) | if the value can not be computed, e.g. because there are unassigned required variables |



