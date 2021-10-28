//[alchemist](../../../index.md)/[it.unibo.alchemist.loader.variables](../index.md)/[JSR223Variable](index.md)

# JSR223Variable

[jvm]\
data class [JSR223Variable](index.md)<[R](index.md)>(**language**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **formula**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) : [DependentVariable](../-dependent-variable/index.md)<[R](index.md)> 

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
| [JSR223Variable](-j-s-r223-variable.md) | [jvm]<br>fun [JSR223Variable](-j-s-r223-variable.md)(language: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), formula: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))<br>builds a new JSR223Variable given a language name and a script. |

## Functions

| Name | Summary |
|---|---|
| [getWith](get-with.md) | [jvm]<br>open override fun [getWith](get-with.md)(variables: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?>): [R](index.md)<br>Given the current controlled variables, computes the current values for this variable. |

## Properties

| Name | Summary |
|---|---|
| [formula](formula.md) | [jvm]<br>val [formula](formula.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>the script that will get interpreted |
| [language](language.md) | [jvm]<br>val [language](language.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>can be the name of the language, the file extension, or its mime type |
