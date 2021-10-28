---
title: getWith
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.loader](../index.html)/[Loader](index.html)/[getWith](get-with.html)



# getWith



[jvm]\
abstract fun <[T](get-with.html), [P](get-with.html) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<[P](../../it.unibo.alchemist.loader.shapes/-rectangle/index.html)>?> [getWith](get-with.html)(values: [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<[String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>): [InitializedEnvironment](../-initialized-environment/index.html)<[T](https://docs.oracle.com/javase/8/docs/api/java/lang/Iterable.html), [P](../../it.unibo.alchemist.loader.shapes/-rectangle/index.html)>



#### Return



an [InitializedEnvironment](../-initialized-environment/index.html) with all the variables set at the specified values. If the value is unspecified, the default is used instead



## Parameters


jvm

| | |
|---|---|
| values | a map specifying name-value bindings for the variables in this scenario |
| <T> | concentration type |
| <P> | position type |




