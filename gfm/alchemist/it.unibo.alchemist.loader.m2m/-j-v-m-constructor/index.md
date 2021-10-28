//[alchemist](../../../index.md)/[it.unibo.alchemist.loader.m2m](../index.md)/[JVMConstructor](index.md)

# JVMConstructor

[jvm]\
sealed class [JVMConstructor](index.md)

A constructor for a JVM class of type [typeName](type-name.md).

## Types

| Name | Summary |
|---|---|
| [Companion](-companion/index.md) | [jvm]<br>object [Companion](-companion/index.md) |

## Functions

| Name | Summary |
|---|---|
| [buildAny](build-any.md) | [jvm]<br>inline fun <[T](build-any.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [buildAny](build-any.md)(factory: Factory): [Result](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-result/index.html)<[T](build-any.md)><br>Provided a JIRF [factory](build-any.md), builds an instance of the requested type [T](build-any.md) or fails gracefully, returning a Result<T>.<br>[jvm]<br>fun <[T](build-any.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [buildAny](build-any.md)(type: [Class](https://docs.oracle.com/javase/8/docs/api/java/lang/Class.html)<out [T](build-any.md)>, factory: Factory): [Result](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-result/index.html)<[T](build-any.md)><br>Provided a JIRF [factory](build-any.md), builds an instance of the requested [type](build-any.md) T or fails gracefully, returning a Result<T>. |
| [parametersFor](parameters-for.md) | [jvm]<br>abstract fun <[T](parameters-for.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [parametersFor](parameters-for.md)(target: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[T](parameters-for.md)>): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<*><br>provided a [target](parameters-for.md) class, extracts the parameters as an ordered list. |

## Properties

| Name | Summary |
|---|---|
| [typeName](type-name.md) | [jvm]<br>val [typeName](type-name.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

## Inheritors

| Name |
|---|
| [OrderedParametersConstructor](../-ordered-parameters-constructor/index.md) |
| [NamedParametersConstructor](../-named-parameters-constructor/index.md) |
