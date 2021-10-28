---
title: AlchemistModelProvider
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.loader](../index.html)/[AlchemistModelProvider](index.html)



# AlchemistModelProvider



[jvm]\
interface [AlchemistModelProvider](index.html)

Translates inputs to a Map representing the Alchemist model.



## Functions


| Name | Summary |
|---|---|
| [from](from.html) | [jvm]<br>open fun [from](from.html)(input: [InputStream](https://docs.oracle.com/javase/8/docs/api/java/io/InputStream.html)): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), *><br>Reads [input](from.html) from an [InputStream](https://docs.oracle.com/javase/8/docs/api/java/io/InputStream.html).<br>[jvm]<br>open fun [from](from.html)(input: [Reader](https://docs.oracle.com/javase/8/docs/api/java/io/Reader.html)): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), *><br>Reads [input](from.html) from a [Reader](https://docs.oracle.com/javase/8/docs/api/java/io/Reader.html).<br>[jvm]<br>open fun [from](from.html)(input: [URL](https://docs.oracle.com/javase/8/docs/api/java/net/URL.html)): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), *><br>Reads [input](from.html) from a [URL](https://docs.oracle.com/javase/8/docs/api/java/net/URL.html).<br>[jvm]<br>abstract fun [from](from.html)(input: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), *><br>Reads [input](from.html) from a [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html). |


## Properties


| Name | Summary |
|---|---|
| [fileExtensions](file-extensions.html) | [jvm]<br>abstract val [fileExtensions](file-extensions.html): [Regex](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.text/-regex/index.html)<br>A [Regex](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.text/-regex/index.html) matching the file extensions supported by this provider. |


## Inheritors


| Name |
|---|
| [YamlProvider](../../it.unibo.alchemist.loader.providers/-yaml-provider/index.html) |

