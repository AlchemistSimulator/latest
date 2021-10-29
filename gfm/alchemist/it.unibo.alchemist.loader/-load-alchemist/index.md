//[alchemist](../../../index.md)/[it.unibo.alchemist.loader](../index.md)/[LoadAlchemist](index.md)

# LoadAlchemist

[jvm]\
object [LoadAlchemist](index.md)

Loads Alchemist simulations from a variety of resources.

## Functions

| Name | Summary |
|---|---|
| [from](from.md) | [jvm]<br>@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()<br>fun [from](from.md)(file: [File](https://docs.oracle.com/javase/8/docs/api/java/io/File.html)): [Loader](../-loader/index.md)<br>Load from a [file](from.md).<br>[jvm]<br>@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()<br>fun [from](from.md)(url: [URL](https://docs.oracle.com/javase/8/docs/api/java/net/URL.html)): [Loader](../-loader/index.md)<br>@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()<br>fun [from](from.md)(url: [URL](https://docs.oracle.com/javase/8/docs/api/java/net/URL.html), model: [AlchemistModelProvider](../-alchemist-model-provider/index.md)): [Loader](../-loader/index.md)<br>Load from an [url](from.md).<br>[jvm]<br>@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()<br>fun [from](from.md)(string: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Loader](../-loader/index.md)<br>Load from a [string](from.md).<br>[jvm]<br>@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()<br>fun [from](from.md)(stream: [InputStream](https://docs.oracle.com/javase/8/docs/api/java/io/InputStream.html), model: [AlchemistModelProvider](../-alchemist-model-provider/index.md)): [Loader](../-loader/index.md)<br>Load from an [InputStream](https://docs.oracle.com/javase/8/docs/api/java/io/InputStream.html).<br>[jvm]<br>@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()<br>fun [from](from.md)(reader: [Reader](https://docs.oracle.com/javase/8/docs/api/java/io/Reader.html), model: [AlchemistModelProvider](../-alchemist-model-provider/index.md)): [Loader](../-loader/index.md)<br>Load from a [reader](from.md).<br>[jvm]<br>@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()<br>fun [from](from.md)(input: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), model: [AlchemistModelProvider](../-alchemist-model-provider/index.md)): [Loader](../-loader/index.md)<br>Load from an [input](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html). |
