//[alchemist](../../../index.md)/[it.unibo.alchemist](../index.md)/[ClassPathScanner](index.md)

# ClassPathScanner

[jvm]\
object [ClassPathScanner](index.md)

An utility class providing support for loading arbitrary subclasses available in the classpath.

## Functions

| Name | Summary |
|---|---|
| [resourcesMatching](resources-matching.md) | [jvm]<br>@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()<br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()<br>fun [resourcesMatching](resources-matching.md)(regex: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), inPackage: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[URL](https://docs.oracle.com/javase/8/docs/api/java/net/URL.html)><br>This function returns a list of all the resources in a certain (optional) package matching a regular expression. |
| [resourcesMatchingAsStream](resources-matching-as-stream.md) | [jvm]<br>@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()<br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()<br>fun [resourcesMatchingAsStream](resources-matching-as-stream.md)(regex: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), inPackage: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[InputStream](https://docs.oracle.com/javase/8/docs/api/java/io/InputStream.html)><br>This function returns a list of all the resources in a certain (optional) package matching a regular expression. |
| [subTypesOf](sub-types-of.md) | [jvm]<br>inline fun <[T](sub-types-of.md)> [subTypesOf](sub-types-of.md)(inPackage: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Class](https://docs.oracle.com/javase/8/docs/api/java/lang/Class.html)<out [T](sub-types-of.md)>><br>@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()<br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()<br>fun <[T](sub-types-of.md)> [subTypesOf](sub-types-of.md)(superClass: [Class](https://docs.oracle.com/javase/8/docs/api/java/lang/Class.html)<[T](sub-types-of.md)>, inPackage: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Class](https://docs.oracle.com/javase/8/docs/api/java/lang/Class.html)<out [T](sub-types-of.md)>><br>This function loads all subtypes of the provided Java class that can be discovered on the current classpath. |
