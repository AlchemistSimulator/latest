//[alchemist](../../../index.md)/[it.unibo.alchemist.loader.m2m](../index.md)/[JVMConstructor](index.md)/[buildAny](build-any.md)

# buildAny

[jvm]\
inline fun <[T](build-any.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [buildAny](build-any.md)(factory: Factory): [Result](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-result/index.html)<[T](build-any.md)>

Provided a JIRF [factory](build-any.md), builds an instance of the requested type [T](build-any.md) or fails gracefully, returning a Result<T>.

[jvm]\
fun <[T](build-any.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [buildAny](build-any.md)(type: [Class](https://docs.oracle.com/javase/8/docs/api/java/lang/Class.html)<out [T](build-any.md)>, factory: Factory): [Result](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-result/index.html)<[T](build-any.md)>

Provided a JIRF [factory](build-any.md), builds an instance of the requested [type](build-any.md) T or fails gracefully, returning a Result<T>.
