---
title: subTypesOf
---
//[alchemist](../../../index.html)/[it.unibo.alchemist](../index.html)/[ClassPathScanner](index.html)/[subTypesOf](sub-types-of.html)



# subTypesOf



[jvm]\




@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()



@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()



fun <[T](sub-types-of.html)> [subTypesOf](sub-types-of.html)(superClass: [Class](https://docs.oracle.com/javase/8/docs/api/java/lang/Class.html)<[T](sub-types-of.html)>, inPackage: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Class](https://docs.oracle.com/javase/8/docs/api/java/lang/Class.html)<out [T](sub-types-of.html)>>



This function loads all subtypes of the provided Java class that can be discovered on the current classpath.



This function cannot use reified and inline (as it should have) due to Java being unaware of the required transformation to use them.





[jvm]\
inline fun <[T](sub-types-of.html)> [subTypesOf](sub-types-of.html)(inPackage: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Class](https://docs.oracle.com/javase/8/docs/api/java/lang/Class.html)<out [T](sub-types-of.html)>>




