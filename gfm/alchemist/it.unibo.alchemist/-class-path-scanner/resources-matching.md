//[alchemist](../../../index.md)/[it.unibo.alchemist](../index.md)/[ClassPathScanner](index.md)/[resourcesMatching](resources-matching.md)

# resourcesMatching

[jvm]\

@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()

@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()

fun [resourcesMatching](resources-matching.md)(regex: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), inPackage: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[URL](https://docs.oracle.com/javase/8/docs/api/java/net/URL.html)>

This function returns a list of all the resources in a certain (optional) package matching a regular expression.

This function cannot use reified and inline (as it should have) due to Java being unaware of the required transformation to use them.
