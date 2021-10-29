---
title: JVMConstructor
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.loader.m2m](../index.html)/[JVMConstructor](index.html)



# JVMConstructor



[jvm]\
sealed class [JVMConstructor](index.html)

A constructor for a JVM class of type [typeName](type-name.html).



## Types


| Name | Summary |
|---|---|
| [Companion](-companion/index.html) | [jvm]<br>object [Companion](-companion/index.html) |


## Functions


| Name | Summary |
|---|---|
| [buildAny](build-any.html) | [jvm]<br>inline fun <[T](build-any.html) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [buildAny](build-any.html)(factory: Factory): [Result](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-result/index.html)<[T](build-any.html)><br>Provided a JIRF [factory](build-any.html), builds an instance of the requested type [T](build-any.html) or fails gracefully, returning a Result<T>.<br>[jvm]<br>fun <[T](build-any.html) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [buildAny](build-any.html)(type: [Class](https://docs.oracle.com/javase/8/docs/api/java/lang/Class.html)<out [T](build-any.html)>, factory: Factory): [Result](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-result/index.html)<[T](build-any.html)><br>Provided a JIRF [factory](build-any.html), builds an instance of the requested [type](build-any.html) T or fails gracefully, returning a Result<T>. |
| [parametersFor](parameters-for.html) | [jvm]<br>abstract fun <[T](parameters-for.html) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [parametersFor](parameters-for.html)(target: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[T](parameters-for.html)>): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<*><br>provided a [target](parameters-for.html) class, extracts the parameters as an ordered list. |


## Properties


| Name | Summary |
|---|---|
| [typeName](type-name.html) | [jvm]<br>val [typeName](type-name.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |


## Inheritors


| Name |
|---|
| [OrderedParametersConstructor](../-ordered-parameters-constructor/index.html) |
| [NamedParametersConstructor](../-named-parameters-constructor/index.html) |

