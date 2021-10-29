---
title: getDependentVariables
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.loader](../index.html)/[Loader](index.html)/[getDependentVariables](get-dependent-variables.html)



# getDependentVariables



[jvm]\
abstract fun [getDependentVariables](get-dependent-variables.html)(): [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<[String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), [DependentVariable](../../it.unibo.alchemist.loader.variables/-dependent-variable/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>>



Allows to access the currently defined dependent variable (those variables whose value can be determined given a valid set of values for the free variables).



#### Return



a [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html) between variable names and their actual representation




