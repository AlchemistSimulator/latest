---
title: JSR223Variable
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.loader.variables](../index.html)/[JSR223Variable](index.html)



# JSR223Variable



[jvm]\
data class [JSR223Variable](index.html)<[R](index.html)>(**language**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **formula**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) : [DependentVariable](../-dependent-variable/index.html)<[R](index.html)> 

This variable loads any [JSR-233](http://archive.fo/PGdk8) language available in the classpath.



## Parameters


jvm

| | |
|---|---|
| R | return type of the variable |
| language | can be the name of the language, the file extension, or its mime type |
| formula | the script that will get interpreted |



## Constructors


| | |
|---|---|
| [JSR223Variable](-j-s-r223-variable.html) | [jvm]<br>fun [JSR223Variable](-j-s-r223-variable.html)(language: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), formula: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))<br>builds a new JSR223Variable given a language name and a script. |


## Functions


| Name | Summary |
|---|---|
| [getWith](get-with.html) | [jvm]<br>open override fun [getWith](get-with.html)(variables: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?>): [R](index.html)<br>Given the current controlled variables, computes the current values for this variable. |


## Properties


| Name | Summary |
|---|---|
| [formula](formula.html) | [jvm]<br>val [formula](formula.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>the script that will get interpreted |
| [language](language.html) | [jvm]<br>val [language](language.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>can be the name of the language, the file extension, or its mime type |

