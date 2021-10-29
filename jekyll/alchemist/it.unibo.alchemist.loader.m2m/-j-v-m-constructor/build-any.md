---
title: buildAny
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.loader.m2m](../index.html)/[JVMConstructor](index.html)/[buildAny](build-any.html)



# buildAny



[jvm]\
inline fun <[T](build-any.html) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [buildAny](build-any.html)(factory: Factory): [Result](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-result/index.html)<[T](build-any.html)>



Provided a JIRF [factory](build-any.html), builds an instance of the requested type [T](build-any.html) or fails gracefully, returning a Result<T>.





[jvm]\
fun <[T](build-any.html) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [buildAny](build-any.html)(type: [Class](https://docs.oracle.com/javase/8/docs/api/java/lang/Class.html)<out [T](build-any.html)>, factory: Factory): [Result](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-result/index.html)<[T](build-any.html)>



Provided a JIRF [factory](build-any.html), builds an instance of the requested [type](build-any.html) T or fails gracefully, returning a Result<T>.




