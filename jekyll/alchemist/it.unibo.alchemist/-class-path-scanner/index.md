---
title: ClassPathScanner
---
//[alchemist](../../../index.html)/[it.unibo.alchemist](../index.html)/[ClassPathScanner](index.html)



# ClassPathScanner



[jvm]\
object [ClassPathScanner](index.html)

An utility class providing support for loading arbitrary subclasses available in the classpath.



## Functions


| Name | Summary |
|---|---|
| [resourcesMatching](resources-matching.html) | [jvm]<br>@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()<br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()<br>fun [resourcesMatching](resources-matching.html)(regex: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), inPackage: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[URL](https://docs.oracle.com/javase/8/docs/api/java/net/URL.html)><br>This function returns a list of all the resources in a certain (optional) package matching a regular expression. |
| [resourcesMatchingAsStream](resources-matching-as-stream.html) | [jvm]<br>@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()<br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()<br>fun [resourcesMatchingAsStream](resources-matching-as-stream.html)(regex: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), inPackage: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[InputStream](https://docs.oracle.com/javase/8/docs/api/java/io/InputStream.html)><br>This function returns a list of all the resources in a certain (optional) package matching a regular expression. |
| [subTypesOf](sub-types-of.html) | [jvm]<br>inline fun <[T](sub-types-of.html)> [subTypesOf](sub-types-of.html)(inPackage: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Class](https://docs.oracle.com/javase/8/docs/api/java/lang/Class.html)<out [T](sub-types-of.html)>><br>@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()<br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()<br>fun <[T](sub-types-of.html)> [subTypesOf](sub-types-of.html)(superClass: [Class](https://docs.oracle.com/javase/8/docs/api/java/lang/Class.html)<[T](sub-types-of.html)>, inPackage: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Class](https://docs.oracle.com/javase/8/docs/api/java/lang/Class.html)<out [T](sub-types-of.html)>><br>This function loads all subtypes of the provided Java class that can be discovered on the current classpath. |

