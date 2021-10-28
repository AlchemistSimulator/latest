---
title: OrderedParametersConstructor
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.loader.m2m](../index.html)/[OrderedParametersConstructor](index.html)



# OrderedParametersConstructor



[jvm]\
class [OrderedParametersConstructor](index.html)(**type**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **parameters**: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<*>) : [JVMConstructor](../-j-v-m-constructor/index.html)

A [JVMConstructor](../-j-v-m-constructor/index.html) whose parameters are an ordered list (common case for any JVM language).



## Constructors


| | |
|---|---|
| [OrderedParametersConstructor](-ordered-parameters-constructor.html) | [jvm]<br>fun [OrderedParametersConstructor](-ordered-parameters-constructor.html)(type: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), parameters: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<*> = emptyList<Any?>()) |


## Functions


| Name | Summary |
|---|---|
| [buildAny](../-j-v-m-constructor/build-any.html) | [jvm]<br>inline fun <[T](../-j-v-m-constructor/build-any.html) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [buildAny](../-j-v-m-constructor/build-any.html)(factory: Factory): [Result](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-result/index.html)<[T](../-j-v-m-constructor/build-any.html)><br>Provided a JIRF [factory](../-j-v-m-constructor/build-any.html), builds an instance of the requested type [T](../-j-v-m-constructor/build-any.html) or fails gracefully, returning a Result<T>.<br>[jvm]<br>fun <[T](../-j-v-m-constructor/build-any.html) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [buildAny](../-j-v-m-constructor/build-any.html)(type: [Class](https://docs.oracle.com/javase/8/docs/api/java/lang/Class.html)<out [T](../-j-v-m-constructor/build-any.html)>, factory: Factory): [Result](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-result/index.html)<[T](../-j-v-m-constructor/build-any.html)><br>Provided a JIRF [factory](../-j-v-m-constructor/build-any.html), builds an instance of the requested [type](../-j-v-m-constructor/build-any.html) T or fails gracefully, returning a Result<T>. |
| [parametersFor](parameters-for.html) | [jvm]<br>open override fun <[T](parameters-for.html) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [parametersFor](parameters-for.html)(target: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[T](parameters-for.html)>): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<*><br>provided a [target](parameters-for.html) class, extracts the parameters as an ordered list. |
| [toString](to-string.html) | [jvm]<br>open override fun [toString](to-string.html)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |


## Properties


| Name | Summary |
|---|---|
| [typeName](index.html#1125071550%2FProperties%2F-134779887) | [jvm]<br>val [typeName](index.html#1125071550%2FProperties%2F-134779887): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

