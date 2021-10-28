//[alchemist](../../../index.md)/[it.unibo.alchemist.loader.providers](../index.md)/[YamlProvider](index.md)

# YamlProvider

[jvm]\
object [YamlProvider](index.md) : [AlchemistModelProvider](../../it.unibo.alchemist.loader/-alchemist-model-provider/index.md)

Loads YAML files via SnakeYAML.

## Functions

| Name | Summary |
|---|---|
| [from](from.md) | [jvm]<br>open override fun [from](from.md)(input: [InputStream](https://docs.oracle.com/javase/8/docs/api/java/io/InputStream.html)): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)><br>Reads [input](from.md) from an [InputStream](https://docs.oracle.com/javase/8/docs/api/java/io/InputStream.html).<br>[jvm]<br>open override fun [from](from.md)(input: [Reader](https://docs.oracle.com/javase/8/docs/api/java/io/Reader.html)): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)><br>Reads [input](from.md) from a [Reader](https://docs.oracle.com/javase/8/docs/api/java/io/Reader.html).<br>[jvm]<br>open override fun [from](from.md)(input: [URL](https://docs.oracle.com/javase/8/docs/api/java/net/URL.html)): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)><br>Reads [input](from.md) from a [URL](https://docs.oracle.com/javase/8/docs/api/java/net/URL.html).<br>[jvm]<br>open override fun [from](from.md)(input: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)><br>Reads [input](from.md) from a [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html). |

## Properties

| Name | Summary |
|---|---|
| [fileExtensions](file-extensions.md) | [jvm]<br>open override val [fileExtensions](file-extensions.md): [Regex](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.text/-regex/index.html)<br>A [Regex](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.text/-regex/index.html) matching the file extensions supported by this provider. |
