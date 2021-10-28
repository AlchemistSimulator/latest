//[alchemist](../../../index.md)/[it.unibo.alchemist.loader.m2m](../index.md)/[NamedParametersConstructor](index.md)

# NamedParametersConstructor

[jvm]\
class [NamedParametersConstructor](index.md)(**type**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **parametersMap**: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<*, *>) : [JVMConstructor](../-j-v-m-constructor/index.md)

A [JVMConstructor](../-j-v-m-constructor/index.md) whose parameters are named and hence stored in a parametersMap (no pure Java class works with named parameters now, Kotlin-only).

## Constructors

| | |
|---|---|
| [NamedParametersConstructor](-named-parameters-constructor.md) | [jvm]<br>fun [NamedParametersConstructor](-named-parameters-constructor.md)(type: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), parametersMap: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<*, *> = emptyMap<Any?, Any?>()) |

## Functions

| Name | Summary |
|---|---|
| [buildAny](../-j-v-m-constructor/build-any.md) | [jvm]<br>inline fun <[T](../-j-v-m-constructor/build-any.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [buildAny](../-j-v-m-constructor/build-any.md)(factory: Factory): [Result](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-result/index.html)<[T](../-j-v-m-constructor/build-any.md)><br>Provided a JIRF [factory](../-j-v-m-constructor/build-any.md), builds an instance of the requested type [T](../-j-v-m-constructor/build-any.md) or fails gracefully, returning a Result<T>.<br>[jvm]<br>fun <[T](../-j-v-m-constructor/build-any.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [buildAny](../-j-v-m-constructor/build-any.md)(type: [Class](https://docs.oracle.com/javase/8/docs/api/java/lang/Class.html)<out [T](../-j-v-m-constructor/build-any.md)>, factory: Factory): [Result](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-result/index.html)<[T](../-j-v-m-constructor/build-any.md)><br>Provided a JIRF [factory](../-j-v-m-constructor/build-any.md), builds an instance of the requested [type](../-j-v-m-constructor/build-any.md) T or fails gracefully, returning a Result<T>. |
| [parametersFor](parameters-for.md) | [jvm]<br>open override fun <[T](parameters-for.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [parametersFor](parameters-for.md)(target: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[T](parameters-for.md)>): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<*><br>provided a [target](parameters-for.md) class, extracts the parameters as an ordered list. |
| [toString](to-string.md) | [jvm]<br>open override fun [toString](to-string.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

## Properties

| Name | Summary |
|---|---|
| [typeName](index.md#1375142642%2FProperties%2F-267951372) | [jvm]<br>val [typeName](index.md#1375142642%2FProperties%2F-267951372): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
